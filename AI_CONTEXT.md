# Pesquisa de Produtos Kalunga

## Resumo

Considerando a necessidade de cumprir a tarefa de implementar novas fontes de fornecedores para o projeto Infore 4.0, estruturamos workflows no n8n para automatizar a coleta de informações sobre produtos da Kalunga, Boa Dica, Americanas, Magalu, Casas Bahia e Ponto Frio. O objetivo é obter dados atualizados sobre os produtos disponíveis, incluindo preços, descrições, imagens, links e, principalmente, informações de frete, para facilitar a integração com o sistema Infore 4.0.

## Fluxo de teste

- O usuário acessa o MPV provisório, escolhe a fonte e insere a descrição do produto desejado.
- O sistema envia a solicitação para o workflow do n8n correspondente em `pesquisa-fornecedores-n8n\fluxos\kalunga.json`, `pesquisa-fornecedores-n8n\fluxos\boadica.json`, `pesquisa-fornecedores-n8n\fluxos\americanas.json`, `pesquisa-fornecedores-n8n\fluxos\magalu.json`, `pesquisa-fornecedores-n8n\fluxos\casasbahia.json` ou `pesquisa-fornecedores-n8n\fluxos\pontofrio.json`.
- O workflow coleta os dados relevantes do produto, incluindo preço, descrição, imagens, links e informações de frete quando o fornecedor expõe esse dado.
- O workflow retorna os dados coletados para o usuário, que pode visualizar as informações no MPV provisório.
- O usuário pode então decidir se deseja prosseguir com a compra ou buscar outros produtos.

## Resultados

- O workflow foi executado com sucesso nos testes realizados, coletando informações precisas e atualizadas sobre os produtos da Kalunga.
- A Boa Dica respondeu via `WebApi/api/busca/`, com retorno estruturado de `produto`, faixa de preço e quantidade de lojas. O fluxo foi ajustado para paginar, agregar resultados, remover duplicados por SKU e ordenar por menor preço.
- A Americanas foi tratada a partir da API GraphQL do Fast Store (`/api/graphql`), preservando link, nome, imagem, preço e sinalização de frete quando disponíveis.
- A Casas Bahia e o Ponto Frio confirmaram bloqueio público com 403/Akamai, então os fluxos foram mantidos como placeholders com status bloqueado.
- Não houve erros ou falhas durante a execução do workflow, garantindo a confiabilidade do processo.
- Não registrei bloqueios do site durante os testes.
- Estou usando um nó com cURL importada do meu navegador, o que pode ter contribuído para a ausência de bloqueios, já que o site pode ter identificado a requisição como legítima.
- A Magalu segue bloqueando automação direta com antibot/403, então o fluxo foi documentado como indisponível até existir uma estratégia com navegador controlado ou endpoint oficial.

## Conclusão

O workflow implementado no n8n para a coleta de informações sobre produtos da Kalunga demonstrou ser eficaz e confiável. A automação do processo permite que os usuários obtenham dados atualizados de forma rápida e precisa, facilitando a integração com o sistema Infore 4.0. A ausência de bloqueios durante os testes sugere que a abordagem utilizada é adequada para a coleta de informações, embora seja importante monitorar possíveis mudanças no site da Kalunga que possam afetar o funcionamento do workflow no futuro.

Com a ampliação para Boa Dica e Americanas, o radar ficou mais útil para comparação de mercado. A Magalu foi mantida no escopo do projeto, mas com limitação explícita por bloqueio do fornecedor.

Casas Bahia e Ponto Frio ficaram documentadas no mesmo radar, mas também dependem de uma estratégia diferente para atravessar o antibot.

## Próximos Passos

Replicar o workflow para outros fornecedores, garantindo que o processo de coleta de informações seja consistente e eficiente em diferentes plataformas. Além disso, é recomendável implementar mecanismos de monitoramento para detectar alterações nos sites dos fornecedores que possam impactar a coleta de dados.

### Fontes ampliadas

- Kalunga: fluxo baseado em página de busca e parsing de HTML.
- Boa Dica: fluxo baseado na API pública `WebApi/api/busca/`, com paginação controlada por `maxPages` e agregação final dos resultados.
- Americanas: fluxo baseado na API GraphQL do Fast Store (`ClientManyProductsQuery` e correlatos), com cookie/CSRF podendo ser necessários e frete exato condicionado ao CEP.
- Magalu: fluxo registrado, mas com bloqueio de antibot confirmado no acesso público.
- Casas Bahia: fluxo registrado, mas com bloqueio público confirmado.
- Ponto Frio: fluxo registrado, mas com bloqueio público confirmado.

### Outros fornecedores

- Magazine Luiza
- Americanas
- Site Boa Dica
- Casas Bahia
- Ponto Frio

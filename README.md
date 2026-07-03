Pesquisa multi-fornecedor — MVP

Pequeno front-end para enviar buscas ao n8n e exibir resultados de produtos de diferentes fornecedores.

Como usar

- Abra `index.html` no navegador para testar localmente.
- Para servir via servidor local (recomendado):

```bash
python -m http.server 8000
```

Em seguida acesse `http://localhost:8000`.

Configuração

- O webhook do n8n agora é selecionado por fornecedor em `index.html`.
- Kalunga, Boa Dica e Americanas têm fluxos próprios em `fluxos/`.
- Magalu, Casas Bahia e Ponto Frio estão documentadas no front-end, mas o acesso público segue bloqueado por antibot.

Deploy no GitHub Pages

1. Garanta que o repositório está no GitHub (já está configurado neste projeto).
2. Vá em **Settings > Pages** no repositório e habilite Pages a partir da branch `main` (root).
3. Aguarde alguns minutos e acesse `https://<seu-usuario>.github.io/<seu-repo>`.

Observações

- O seletor de fonte permite alternar entre Kalunga, Boa Dica, Americanas, Casas Bahia, Ponto Frio e Magalu.
- A Boa Dica busca varias paginas quando `maxPages` e enviado no corpo do webhook, limitado a 5 paginas por execucao.
- A Americanas usa o endpoint GraphQL do Fast Store, então cookie e CSRF do navegador podem ser úteis quando o retorno vier vazio.
- O botão "Comprar" foi removido — permanece apenas "Ver Produto".
- Os produtos são ordenados por preço (menor para maior) antes de exibidos.

Licença

Projeto pessoal.

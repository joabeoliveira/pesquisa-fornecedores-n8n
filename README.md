Pesquisa Kalunga — MVP

Pequeno front-end para enviar buscas ao n8n e exibir resultados de produtos.

Como usar

- Abra `index.html` no navegador para testar localmente.
- Para servir via servidor local (recomendado):

```bash
python -m http.server 8000
```

Em seguida acesse `http://localhost:8000`.

Configuração

- O webhook do n8n está definido em `index.html` na constante `WEBHOOK_URL`.
- Atualize esse valor para o seu endpoint n8n se necessário.

Deploy no GitHub Pages

1. Garanta que o repositório está no GitHub (já está configurado neste projeto).
2. Vá em **Settings > Pages** no repositório e habilite Pages a partir da branch `main` (root).
3. Aguarde alguns minutos e acesse `https://<seu-usuario>.github.io/<seu-repo>`.

Observações

- O botão "Comprar" foi removido — permanece apenas "Ver Produto".
- Os produtos são ordenados por preço (menor para maior) antes de exibidos.

Licença

Projeto pessoal.

# Site da Duon

Site estático (HTML, CSS e JavaScript puros, sem build). Publicado pelo GitHub Pages a partir da raiz da branch `main`.

- `index.html`: página principal.
- `privacidade.html`, `reembolso.html`, `termos.html`, `404.html`: páginas de texto, com o estilo de `paginas.css`.

## Publicar uma mudança

Edite o arquivo, depois `git add -A && git commit -m "..." && git push`. O GitHub Pages atualiza em cerca de um minuto.

## Voltar atrás

`git revert <commit>` e `git push`.

## O que nunca fazer

Nunca colocar a chave secreta da Stripe (`sk_...`) neste repositório: ele é público. Para vender, use links de pagamento da Stripe.

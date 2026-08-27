# Site — Bartoski Engenharia

Página única e autocontida.

- `index.html` — o site inteiro. Sem build, sem dependência, sem requisição externa.

A fonte de verdade é `apps/site/index.html` no monorepo privado
`imanrelb-hue/ecossistema-bartoski`. Este repositório é público **apenas**
porque o GitHub Pages não publica repositório privado em conta gratuita.

Nada de dado sensível entra aqui. Só esta página.

## Domínio

O `CNAME` será recriado pelo próprio GitHub quando `imanrel.com.br` for
cadastrado em Settings > Pages > Custom domain. Ele foi removido do primeiro
commit de propósito: com o CNAME presente e o DNS ainda sem resolver, o Pages
redireciona o endereço `github.io` para um domínio morto e o site fica
inacessível pelos dois caminhos.

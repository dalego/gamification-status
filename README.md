# gamification-status

Página pública de status da dalego (status.dalego.com). HTML sem build, servida pelo Cloudflare Pages
a partir deste repositório: push na `main` publica.

Lê o estado de https://dalego.betteruptime.com/index.json (página 269058 do Better Stack) a cada minuto.
A página mostra API, Painel e Site. O Webinar tem monitor no Better Stack, mas fica fora da página.

Para mudar o que aparece (nome, ordem, incluir ou tirar um serviço), mexa nos recursos da página
269058 no Better Stack; este HTML só desenha o que vem de lá.

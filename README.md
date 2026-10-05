# Juntos Somos Mais Fortes — Website institucional 3D

Uma única página (`index.html`) em HTML, CSS e JavaScript. O símbolo em 3D usa Three.js (r128), carregado por CDN. As fontes vêm do Google Fonts.

## Ficheiros
- `index.html`: o site completo
- `logo-jsmf.svg`: o símbolo em vector, redesenhado a partir do logótipo, para usar noutros materiais

## Secções
Início (símbolo 3D) · A marca · O símbolo · Porquê integridade · Serviços (4 áreas) · Quem servimos · Valores (carrossel 3D) · Metodologia · Impacto · Perguntas frequentes · Contacto

## Onde editar
- Serviços: array `services` no script
- Valores: array `values` no script
- Formas 3D do símbolo: funções `body()`, `bar()` e `head()` no script

## A substituir antes de publicar
- `[EMAIL]`, `[TELEFONE]` e `[ENDEREÇO]` no HTML e a constante `CONTACT_EMAIL` no script. O formulário abre o programa de email do visitante com a mensagem pronta. Para receber os pedidos directamente, ligue-o a um serviço como Formspree ou ao backend do vosso alojamento.
- Confirmar os números de impacto (+10, +50, +30).
- Rever os textos de interpretação do símbolo e da missão com a direcção da marca.

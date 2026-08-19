# Catálogo J. Edivaldo Arte Sacra

Catálogo online de peças litúrgicas (candelabras, altares sacros) da J. Edivaldo Arte Sacra — São João Del Rei, MG.

Site estático em HTML/CSS/JS puro (sem build, sem dependências). Solicitação de orçamento integrada com WhatsApp.

## Estrutura
- `index.html` — página completa do catálogo (estilos, produtos e lógica no mesmo arquivo)
- `images/` — fotos dos produtos, organizadas em subpastas por conjunto/produto

## Editar produtos
Abra o `index.html` e procure o array `products` dentro da tag `<script>`. Cada produto tem nome, categoria, medidas, preços e um array `images` (pode ter várias fotos — o site já mostra galeria automaticamente quando há mais de uma).

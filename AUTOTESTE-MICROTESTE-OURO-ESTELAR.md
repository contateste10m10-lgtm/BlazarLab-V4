# BlazarLab — Microteste Ouro Estelar

## Escopo
Protótipo visual separado, baseado na versão BlazarLab v1.3.40. Não modifica nem publica o site oficial. Os três fundos são artes vetoriais conceituais para avaliar a composição visual — não são simulações físicas.

## Resultado dos autotestes

- **45/45 verificações aprovadas** no Chromium.
- **0 erros de JavaScript/console** observados durante esta execução.
- Interface completa renderizada em desktop (1280 × 900) e em viewport mobile emulado (390 × 844).
- Verificada a alternância entre tema claro/escuro e os fundos Anel de Einstein, Horizonte de Eventos e Teia Cósmica.
- O SVG da curva de luz demonstrativa permaneceu idêntico quando apenas o fundo mudou nos três casos verificados.
- Sem rolagem horizontal indevida no desktop/mobile testados; os links internos resolvem e não foram encontrados IDs duplicados.
- O seletor visual foi aberto e verificado dentro da área visível mobile.

## Limites
Este microteste **não** é uma auditoria extensa do site: não inclui teste físico em iPhone/Safari ou Android, leitores de tela reais, comparação com diferentes versões de navegador nem validação de publicação no GitHub Pages. Os resultados valem para esta prévia no Chromium emulado e não garantem comportamento em todos os aparelhos.

## Como experimentar
Abra `BlazarLab-Ouro-Estelar-Microteste.html` (arquivo independente) ou extraia `blazarlab-ouro-estelar-microteste.zip` e abra `index.html`. No cabeçalho, abra o seletor de opções visuais, escolha **Ouro Estelar** e alterne os três fundos. A prévia começa com Anel de Einstein selecionado.

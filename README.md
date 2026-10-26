# Atelier Anatómico 3D

Protótipo de estúdio 3D para referências de desenho da figura humana.

## Utilização

Abre `index.html` num navegador moderno com acesso à Internet. Caso o navegador impeça módulos no protocolo `file://`, inicia um servidor local nesta pasta com `python -m http.server 8000` e abre `http://localhost:8000`.

## Funcionalidades

- Corpo inteiro, cabeça, busto, tronco, mãos e pernas, com zoom dedicado.
- Órbita livre, seis vistas predefinidas, perspetiva e projeção ortográfica.
- Camadas visuais de superfície, ossos e músculos esquemáticos; combinação de camadas e opacidade.
- Luz principal com direção, elevação, intensidade, temperatura e iluminação ambiente.
- Linhas de construção, grelha, eixo de simetria, wireframe, rotação automática.
- Controlos de abertura dos braços, rotação/inclinação da cabeça, proporções do corpo.
- Ambiente configurável, captura PNG e interface responsiva.

## Limitações

O modelo é **esquemático** e não constitui uma representação anatómica cientificamente rigorosa. As mãos, músculos e ossos são simplificados, e não há ainda articulações individuais completas nem biblioteca de poses. Para uma versão profissional deverá ser integrado um modelo humano anatómico 3D com licenciamento apropriado (e diferentes tipos de corpo), controlos de rigging, músculos e ossos separados e seleção por estrutura.

## Dependências

Three.js v0.165 via CDN jsDelivr (requer Internet). Não recolhe dados pessoais nem envia imagens para servidores.
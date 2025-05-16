
# Jogo de Naves

Este projeto é uma simulação simples e divertida de um jogo de naves espaciais(piu, piu, piu) desenvolvido com HTML, CSS e JavaScript puro. Nele, o jogador controla uma nave que pode se mover e atirar para destruir inimigos que aparecem na tela, testando reflexos e coordenação.

## Objetivo

O principal objetivo do jogo é atingir a maior pontuação possível, destruindo as naves inimigas que surgem progressivamente. A cada acerto, o jogador ganha pontos. Se uma nave inimiga colidir com a sua, o jogo termina.

## Funcionalidades

- Controle da nave com teclado (setas ou WASD)
- Disparo de projéteis com tecla espaço
- Naves inimigas com movimentação automática
- Detecção de colisões entre projéteis e inimigos
- Contador de pontos
- Tela de "game over" com opção de reiniciar

## Tecnologias Utilizadas

- HTML5 para estrutura da página
- CSS3 para estilização dos elementos visuais
- JavaScript (vanilla) para a lógica do jogo, movimentação, colisões e interações

## Organização do Projeto

```
Jogo-de-Naves/
├── index.html        # Estrutura do jogo
├── style.css         # Estilo e design dos elementos
└── script.js         # Lógica de movimentação, colisão e pontuação
```

## Como Jogar

1. Clone ou baixe este repositório:
   git clone https://github.com/luxasfn/-Jogo-de-Naves.git

2. Abra o arquivo index.html no seu navegador.

3. Utilize as teclas direcionais (ou WASD) para mover a nave.

4. Pressione a barra de espaço para atirar.

5. Tente destruir o maior número possível de inimigos antes que eles colidam com você.

## Aprendizados

Este projeto proporcionou um aprendizado prático e completo sobre como criar jogos interativos no navegador utilizando apenas JavaScript puro, sem o uso de bibliotecas externas ou engines de game development. Entre os principais aprendizados, destacam-se:

### Lógica de Game Loop

- Implementação de um game loop manual com setInterval e requestAnimationFrame, responsável por atualizar a tela constantemente, processar movimentos, detectar colisões e redesenhar elementos.
- Compreensão do ciclo contínuo de execução necessário para jogos baseados em eventos e tempo real.

### Manipulação do DOM e posicionamento

- Uso de propriedades como style.left e style.top para movimentar elementos na tela em tempo real.
- Criação e remoção dinâmica de elementos (createElement e remove) para representar projéteis e inimigos durante o jogo.

### Controle com teclado (event listeners)

- Captação precisa de eventos de teclado com keydown e keyup, implementando suporte a múltiplas teclas simultâneas.
- Simulação de movimentação contínua e controle de disparos com base em lógica condicional e estados.

### Detecção de colisões

- Implementação de uma função de colisão entre elementos HTML com base em coordenadas e dimensões (getBoundingClientRect).
- Detecção precisa de impacto entre tiros e inimigos, além da colisão entre a nave do jogador e naves inimigas.

### Organização do código e estados

- Controle de variáveis de estado como pontuação, vidas, velocidade dos inimigos, e condição de fim de jogo.
- Separação clara entre lógica de atualização (gameplay), renderização e controle de entrada.

### Criação de HUDs e feedback visual

- Atualização em tempo real de elementos como a pontuação e mensagem de “Game Over”.
- Exibição e ocultação de elementos com base no estado do jogo.

Este projeto também serviu como uma excelente introdução à lógica de jogos 2D no navegador, reforçando o raciocínio algorítmico e o domínio da linguagem JavaScript para aplicações interativas.

## Licença

Este projeto está sob a licença MIT. É tudo nosso!☭ sinta-se à vontade para modificar e utilizar como base para outros jogos ou estudos.

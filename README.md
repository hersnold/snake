```markdown
# Snake Game

Este é um jogo Snake desenvolvido em Python utilizando a biblioteca `pygame`.

## Descrição

O jogo Snake é um jogo clássico onde o jogador controla uma cobra que cresce ao comer comida. O objetivo é comer a comida e evitar colisões com as bordas da tela e com o próprio corpo da cobra. O jogo oferece 3 vidas por rodada, e a pontuação aumenta a cada comida consumida.

## Funcionalidades

- Controle a cobra usando as teclas de seta (cima, baixo, esquerda, direita).
- A cobra cresce ao comer a comida.
- O jogo termina quando a cobra perde todas as vidas.
- Pontuação exibida na tela.
- A cobra perde uma vida ao colidir com a borda ou com seu próprio corpo.

## Requisitos

- Python 3.x
- Biblioteca `pygame`

## Instalação

1. Clone este repositório:

   ```sh
   git clone https://github.com/hersnold/snake.git
   cd snake
   ```

2. Instale a biblioteca `pygame`:

   ```sh
   pip install pygame
   ```

## Como Jogar

1. Execute o jogo:

   ```sh
   python snake_game.py
   ```

2. Use as teclas de seta para controlar a direção da cobra.
3. Coma a comida (quadrado verde) para aumentar a pontuação e o tamanho da cobra.
4. Evite colisões com as bordas da tela e com o próprio corpo da cobra.
5. Você tem 3 vidas. O jogo termina quando todas as vidas são perdidas.
6. Para reiniciar o jogo após uma perda, pressione a tecla 'C'. Para sair do jogo, pressione a tecla 'Q'.

## Estrutura do Código

O código está dividido em duas classes principais:

1. **Classe Snake**:
   - Mantém uma lista de segmentos que compõem a cobra.
   - Atualiza a posição da cobra baseada na direção.
   - Verifica colisões com a borda e consigo mesma.
   - Método `grow` para adicionar um novo segmento à cobra quando ela come a comida.

2. **Classe Food**:
   - Desenha a comida na tela.
   - Método `reposition` para reposicionar a comida quando a cobra a come.

### Funções Auxiliares

- `message(msg, color, x, y)`: Função para exibir mensagens na tela.
- `gameLoop()`: Função principal do jogo que contém a lógica do jogo.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

```



4. **Screenshots (Opcional)**:
   Adicione screenshots do jogo no `README.md` para tornar o projeto mais atraente. Use a sintaxe ![alt text](caminho/para/screenshot.png) para incluir imagens.

Se precisar de mais alguma coisa, estou à disposição!

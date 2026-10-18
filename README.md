## 2. README do Jogo 2D (HTML5 Canvas)

```markdown
# 2D Arcade Neon Dodger (HTML5 Canvas)

Um jogo arcade 2D viciante de sobrevivência construído em **HTML5 Canvas**, **Tailwind CSS** e **JavaScript puro**. O objetivo é desviar de obstáculos geométricos vermelhos enquanto coleta esferas azuis brilhantes em um campo de jogo dinâmico.

---

## 🚀 Funcionalidades
* **Motor Gráfico em Canvas 2D:** Renderização fluida a 60 FPS com efeitos de rastro (*trail*), partículas de colisão e glowing neon.
* **Dificuldade Progressiva:** A velocidade e a taxa de surgimento dos obstáculos aumentam à medida que sua pontuação cresce.
* **Suporte a Múltiplos Controles:** Compatível com teclado (WASD / Setas) e movimento baseado em cursor do mouse ou toque na tela.
* **Design Minimalista Dark Mode:** Interface elegante com painéis translúcidos e indicadores visuais de vidas e pontuação máxima (*High Score*).

---

## 🎮 Controles
* **Teclado:** Utilize as teclas `W`, `A`, `S`, `D` ou as **Setas Direcionais** para mover o jogador.
* **Mouse/Toque:** Arraste o cursor ou toque na tela para guiar o personagem diretamente.
* **Reiniciar:** Pressione `Enter` ou clique no botão de reiniciar após perder todas as vidas.

---

## 🛠️ Como Executar
Este jogo é totalmente autossuficiente e roda diretamente no navegador sem dependências complexas.

1. Salve o código do jogo em um arquivo chamado `game.html`.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

---

## 📦 Tecnologias Utilizadas
* **HTML5 Canvas API** para renderização gráfica e física 2D.
* **Tailwind CSS** para estilização da interface e layout responsivo.
* **Vanilla JavaScript** para gerenciamento de estado, loop de jogo (*requestAnimationFrame*) e detecção de colisão AABB/Circular.

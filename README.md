# 🎮 Plataforma 2D — Godot Engine 4

Jogo de plataforma 2D desenvolvido do zero na **Godot Engine 4**. Este repositório registra a evolução do projeto, abrangendo a estruturação de cenas, scripts de física, configuração de colisões e mapeamento de controles.

---

## 📌 Sobre o Projeto

O projeto consiste em uma base para jogos de plataforma em pixel art / 2D, focando em uma movimentação fluida para o jogador, organização limpa de nós no ecossistema da Godot e gerenciamento otimizado de colisões.

---

## 🚀 Recursos e Funcionalidades

* 🏃 **Movimentação do Jogador**: Mecânicas integradas para caminhar, pular e agachar.
* 🎯 **Matriz de Colisões 2D**: Camadas de física (Physics Layers) configuradas para:
  * `Layer 1`: Terreno (`terrain`)
  * `Layer 2`: Jogador (`player`)
  * `Layer 3`: Inimigos (`enemies`)
  * `Layer 4`: Fim de fase (`level_end`)
* 📱 **Resolução e Pixel Art**: Viewport configurado em `400x208` com filtro de textura padrão desativado (Nearest/Pixel Perfect).
* ⚙️ **Física**: Suporte e otimização configurados para a Godot 4.6.

---

## 🎮 Controles Padrão (Input Map)

| Ação | Teclas Padrão |
| :--- | :--- |
| **Mover para Esquerda** | <kbd>A</kbd> ou <kbd>Seta Esquerda</kbd> |
| **Mover para Direita** | <kbd>D</kbd> ou <kbd>Seta Direita</kbd> |
| **Pular** | <kbd>Espaço</kbd>, <kbd>W</kbd> ou <kbd>Seta Cima</kbd> |
| **Agachar** | <kbd>S</kbd> ou <kbd>Seta Baixo</kbd> |

---

## 🛠️ Tecnologias Utilizadas

* **Engine**: [Godot Engine 4.6](https://godotengine.org/)
* **Linguagem**: GDScript
* **Renderizador**: Mobile / Vulkan / Direct3D 12

---

## 💻 Como Executar o Projeto Localmente

1. Certifique-se de ter a **Godot Engine 4.x** instalada em seu computador.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/godot-2d-platformer.git](https://github.com/SEU_USUARIO/godot-2d-platformer.git)

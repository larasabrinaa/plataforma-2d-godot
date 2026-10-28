# 🎮 Plataforma 2D — Godot Engine 4

Jogo de plataforma 2D desenvolvido do zero na **Godot Engine 4**. Este repositório registra a evolução do projeto, incluindo a estruturação de cenários, scripts de física, mapeamento de controlos e mecânicas do jogador.

---

## 📸 Screenshots do Jogo

<img width="500" height="300" alt="Captura de tela 2026-10-28 135540" src="https://github.com/user-attachments/assets/c63d4553-2cca-4eb7-9f30-60f1b1cd5098" /> <img width="500" height="300" alt="Captura de tela 2026-10-28 135528" src="https://github.com/user-attachments/assets/8cb93f9f-d32e-4cec-ba6f-1c7e0df7b293" />



---

## 📌 Sobre o Projeto

O projeto é uma base para jogos de plataforma em *pixel art*, focando numa movimentação fluida do jogador, na organização limpa de nós (*nodes*) na Godot 4 e na gestão otimizada de colisões para diferentes elementos do mapa.

---

## 🚀 Recursos e Funcionalidades

* 🏃 **Movimentação do Jogador**: Mecânicas integradas para caminhar, pular e agachar.
* 🎯 **Matriz de Colisões 2D**: Camadas de física (*Physics Layers*) configuradas para:
  * `Layer 1`: Terreno (`terrain`)
  * `Layer 2`: Jogador (`player`)
  * `Layer 3`: Inimigos (`enemies`)
  * `Layer 4`: Fim de fase (`level_end`)
* 📱 **Resolução e Pixel Art**: Viewport configurado em `400x208` com filtro de textura padrão desativado (Nearest / Pixel Perfect).
* ⚙️ **Física**: Suporte e otimizações configuradas para a Godot 4.6.

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

1. Certifica-te de ter a **Godot Engine 4.x** instalada no teu computador.
2. Clona este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/godot-2d-platformer.git](https://github.com/SEU_USUARIO/godot-2d-platformer.git)

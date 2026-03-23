# DeepSeaRescue 🌊

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Curso](https://img.shields.io/badge/Curso-Sistemas%20de%20Informa%C3%A7%C3%A3o-blue)
![Instituição](https://img.shields.io/badge/Institui%C3%A7%C3%A3o-Uninter-yellow)

O **DeepSeaRescue** é um projeto de jogo desenvolvido como Trabalho Prático para o curso de **Sistemas de Informação da Uninter**. O foco principal do desenvolvimento foi a aplicação de lógica de programação pura, gestão de estados de jogo e a implementação de sistemas de física básica.

---

## 🚀 O Desafio Técnico

O maior desafio deste projeto foi tirar a ideia do papel e enfrentar a **complexidade da implementação da lógica de colisão**. Diferente do uso de motores prontos que abstraem essa camada, o desenvolvimento exigiu:

* **Cálculo de Bounding Boxes:** Implementação manual da detecção de interseção entre coordenadas $X$ e $Y$.
* **Tratamento de Sobreposição:** Lógica para impedir que o personagem "atravesse" objetos sólidos ou saia dos limites da tela.
* **Performance:** Garantir que a verificação de colisão ocorra em tempo real dentro do Game Loop sem causar quedas de frames.

A transição da teoria matemática para a "mão na massa" no código foi fundamental para consolidar os conceitos de geometria analítica aplicados à computação.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Biblioteca:** Pygame
* **Paradigma:** Programação Orientada a Objetos (POO)

---

## 🎮 Como Jogar

### Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina. Você também precisará da biblioteca Pygame.

```bash
pip install pygame

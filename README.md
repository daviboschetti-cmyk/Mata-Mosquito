# 🦟 Mata Mosquito

Um jogo de navegador onde o objetivo é eliminar os mosquitos antes que eles escapem.

O jogo possui diferentes níveis de dificuldade e utiliza a câmera do computador para permitir que o jogador interaja com o jogo usando os movimentos da mão.

---

## 🎮 Sobre o projeto

O **Mata Mosquito** foi desenvolvido como um projeto web utilizando HTML, CSS e JavaScript.

A ideia principal é criar uma experiência diferente de um jogo tradicional, permitindo que o jogador use a própria mão para tentar acertar os mosquitos na tela.

---

## 🕹️ Como jogar

1. Abra a página inicial do jogo.
2. Escolha uma dificuldade.
3. Clique em **Jogar**.
4. Permita o acesso à câmera quando o navegador solicitar.
5. Posicione sua mão na frente da câmera.
6. Feche a mão sobre o mosquito para tentar acertá-lo.
7. Cada mosquito acertado aumenta sua pontuação.
8. Se o mosquito mudar de posição antes de ser acertado, você perde uma vida.
9. O jogador começa com **3 vidas**.
10. Quando as vidas acabam, o jogo termina.

Também é possível clicar no mosquito com o mouse.

---

## ⭐ Sistema de pontuação

Cada mosquito acertado vale:

**+10 pontos**

O jogo também possui um sistema de **recorde**, que fica salvo no navegador utilizando `localStorage`.

Assim, o recorde continua salvo mesmo depois de fechar e abrir o jogo novamente.

---

## ❤️ Sistema de vidas

O jogador começa com:

**❤️ 3 vidas**

Quando o mosquito não é acertado dentro do tempo determinado, uma vida é perdida.

Quando as vidas chegam a zero, aparece a tela de **Game Over**.

---

## 📷 Reconhecimento da mão

O projeto utiliza a biblioteca **MediaPipe Hands** para detectar a posição da mão através da câmera.

O sistema identifica os movimentos da mão e verifica quando ela está fechada.

Quando a mão fechada está sobre o mosquito, o jogo considera que o mosquito foi acertado.

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- MediaPipe Hands
- Web Camera API
- LocalStorage

---

## 📁 Estrutura do projeto

```text
APP-CLIENTE/
│
├── CSS/
│   ├── style.css
│   └── style2.css
│
├── IMAGE/
│   ├── Fundo.png
│   ├── muqitinho.png
│   └── download (7).png
│
├── JS/
│   ├── script.js
│   └── menu.js
│
├── Baby.html
├── index.html
└── README.md

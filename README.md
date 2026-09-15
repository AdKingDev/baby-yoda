# 👽 Baby Yoda em CSS

Uma ilustração animada inspirada no **Baby Yoda**, criada utilizando apenas **HTML e CSS**.

O objetivo do projeto foi explorar como formas, gradientes, pseudo-elementos e animações CSS podem ser combinados para construir uma ilustração sem utilizar imagens ou JavaScript.

## 💡 Sobre o projeto

O personagem é construído a partir de apenas um elemento HTML:

```html
<div class="baby-yoda"></div>
```

Toda a aparência é criada através do CSS.

A cabeça utiliza propriedades como `border-radius` e `radial-gradient`, enquanto as orelhas são construídas com os pseudo-elementos `::before` e `::after`.

Além da ilustração, pequenas animações dão movimento aos olhos e às orelhas do personagem.

## 🎨 Construção visual

A composição utiliza diferentes técnicas de CSS:

* `border-radius` para criar formas arredondadas;
* `radial-gradient()` para desenhar os olhos;
* `::before` e `::after` para criar as orelhas;
* CSS Custom Properties para reutilizar as principais cores;
* posicionamento absoluto para organizar os elementos;
* `transform` para movimentar as orelhas.

Isso permite construir todo o personagem sem utilizar arquivos de imagem.

## ✨ Animações

O projeto possui três animações principais:

### 👀 Olhos

A animação modifica o tamanho dos gradientes responsáveis pelos olhos, criando um efeito de piscada.

### 👂 Orelha esquerda

Utiliza `transform: rotate()` para movimentar suavemente uma das orelhas.

### 👂 Orelha direita

Aplica a mesma técnica no sentido oposto, criando um movimento simétrico.

As animações utilizam `@keyframes`, `cubic-bezier()` e `alternate` para deixar o movimento contínuo e mais natural.

## 🛠️ Tecnologias

* **HTML5** — estrutura mínima da ilustração;
* **CSS3** — desenho, posicionamento e animações.

## 🧠 Conceitos praticados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* CSS Custom Properties;
* Pseudo-elementos `::before` e `::after`;
* `position: relative` e `absolute`;
* `z-index`;
* `border-radius`;
* Gradientes;
* `transform`;
* `transform-origin`;
* `@keyframes`;
* `animation`;
* `cubic-bezier()`;
* Unidades relativas com `em`.

## 📄 Licença

Este projeto está sob a licença MIT.

---

Desenvolvido por **Adriano Júnio**.

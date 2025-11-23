# 🐷 My Chubby Little Piggy

> Um aplicativo de gamificação financeira que torna o hábito de poupar divertido e visualmente recompensador.

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
![Badge HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Badge JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📱 Sobre o Projeto

O **My Chubby Little Piggy** (Meu Porquinho Gordinho) nasceu da necessidade de criar uma ferramenta visual para acompanhar metas financeiras de longo prazo. Diferente de planilhas complexas, ele utiliza o conceito de **gamificação**: o usuário "compra" números em uma grade, depositando o valor correspondente em sua conta bancária real.

O projeto é uma **Web Application (SPA)** responsiva, otimizada para uso em dispositivos móveis (Mobile First), funcionando como um companheiro de bolso para o poupador.

---

## 📸 Demonstração Visual

![Screenshot do App](./screenshot_app.jpg)
*(Adicione um print da tela do seu app aqui no repositório com o nome screenshot_app.png)*

👉 **[Acesse o projeto online aqui](https://ericapmello.github.io/My-chubby-little-piggy-/)**

---

## 🧠 A Lógica Matemática (Soma de Gauss)

Um dos maiores desafios técnicos foi: *Como criar uma meta de R$ 1.000.000,00 sem travar o navegador com 1 milhão de botões?*

Para resolver isso, apliquei a lógica da **Progressão Aritmética** (famosa história da Soma de Gauss). O app não cria um botão para cada Real. Ele calcula quantos números sequenciais (1, 2, 3...) são necessários para que a soma deles atinja a meta.

A fórmula utilizada no algoritmo foi a inversão da soma de PA:
$$S_n = \frac{n(a_1 + a_n)}{2}$$

Isso permite que o app seja extremamente performático. Por exemplo:
* Para juntar **R$ 10.000,00**, geramos apenas **141 botões**.
* Isso garante leveza no processamento e uma interface limpa (UX).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estrutura da aplicação.
* **CSS3 Moderno:** Uso de Flexbox, CSS Grid para a grade responsiva, animações (Keyframes) e variáveis. Design focado em UI "Kawaii" (fofo) e acessibilidade.
* **Vanilla JavaScript (ES6+):**
    * Manipulação do DOM.
    * Lógica matemática para geração dinâmica de elementos.
    * **LocalStorage:** Persistência de dados no navegador do cliente (Client-side storage), garantindo privacidade e funcionamento offline.

---

## ✨ Funcionalidades

- [x] **Metas Dinâmicas:** Seleção de objetivos de R$ 10k a R$ 1 Milhão.
- [x] **Persistência de Dados:** O app lembra o progresso mesmo se fechar o navegador.
- [x] **Feedback Tátil:** Vibração ao interagir com os botões (Haptic Feedback).
- [x] **Tutorial Interativo:** Modal de boas-vindas para novos usuários.
- [x] **Responsividade:** Layout adaptável para Desktop e Mobile.

---

## 🚀 Como rodar este projeto localmente

1. Clone este repositório:
```bash
git clone [https://github.com/EricaPMello/My-chubby-little-piggy-.git](https://github.com/EricaPMello/My-chubby-little-piggy-.git)

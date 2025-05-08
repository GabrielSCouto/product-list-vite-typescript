# Frontend Mentor - Lista de Produtos com Carrinho

## Boas-vindas! 👋

Esse é um desafio de front-end do [Frontend Mentor](https://www.frontendmentor.io).

Esta solução foi construída usando apenas **HTML**, **CSS**, TypeScript e **Vite**, respeitando o design original e entregando funcionalidades completas de carrinho com layout responsivo.

## 🔧 Funcionalidades Desenvolvidas

* 🍰 Renderização dinâmica dos produtos via array TypeScript
* 🛒 Adicionar e remover produtos do carrinho
* ➕➖ Ajustar quantidade de itens diretamente no carrinho
* 💵 Cálculo automático de subtotal e total da compra
* 📱 Layout responsivo para desktop e mobile
* 🧾 Resumo do pedido com contador de itens
* 🌿 Mensagem de entrega neutra em carbono

## 📁 Estrutura de Pastas

```
├── Cart.ts          # Manipulação do carrinho
├── Desserts.ts      # Manipulação das sobremesas
├── index.html       # Página principal do HTML
├── style.css        # Estilos do layout
├── data.json        # Json com dados das sobremesas
├── assets/images/   # Imagens dos produtos utilizadas no projeto 
```

## 🧑‍🍳 Produtos

Os produtos são carregados dinamicamente através de um array JavaScript dentro do data.json. Exemplo:

```json
{
  "id": 1,
  "name": "Waffle com Frutas Vermelhas",
  "type": "Waffle",
  "price": 6.5,
  "image": "./assets/images/waffle.jpg"
}
```

> 📦 Você pode editar nomes, preços ou imagens à vontade.

## 🚀 Como rodar o projeto

1. Clone este repositório
2. Adicione suas imagens na pasta `./assets/images/`
3. Abra o arquivo `index.html` no navegador — não precisa de build ou servidor

## 🌍 Publicar o projeto

Você pode hospedar gratuitamente usando:

* [GitHub Pages](https://pages.github.com/)
* [Netlify](https://netlify.com/)
* [Vercel](https://vercel.com/)

## 🤝 Contribua ou envie feedback

Este projeto é ótimo para aprendizado. Fique à vontade para contribuir, clonar, testar e sugerir melhorias.

## 🧠 Aprendizados

* Manipulação de DOM com TypeScript
* Controle de estado via objetos TS
* HTML semântico e acessível
* Design responsivo com `flex` e `grid`
* Estilização baseada em guias visuais reais

---

### 👨‍💻 Autores

Desenvolvido por Gabriel Couto & Gabriel Bagetti, baseado no desafio [Frontend Mentor - Product List with Cart](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d).

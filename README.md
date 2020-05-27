<h1 align="center">
  <img src="src/assets/logo.png">
</h1>

<h1 align="center">
  <img width="30%" src="https://ik.imagekit.io/avcuvi78yk/ezgif.com-resize_FwiNXdT0m.gif">
</h1>

# Index

- [Sobre](#-sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)
- [Utilizando a fake API](#-utilizando-a-fake-api)

## 📋 Sobre

O projeto **GoMarketplace** é um desafio do curso de fundamentos React Native. O desafio foi criar um e-commerce de vendas de roupas.

---

## 🚀 Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [React Native](https:https://reactnative.dev)
- [TypeScript](https://www.typescriptlang.org/)
- [React Hooks](https://pt-br.reactjs.org/docs/hooks-intro)
- [Axios](https://githu.com/axios/axios)

---

## 📂Como baixar o projeto

```bash
# Clonar o repositório
$ git clone https://github.com/pedroguilhermesilva/fundamentos-react-native

# Entrar no diretório do projeto
$ cd fundamentos-react-native

# Instalar as dependências
$ yarn install

# Iniciar o projeto
$ yarn start
```

**Atenção:** Caso você esteja emulando no iOS, na pasta do seu projeto navegue até a pasta ios executando o comando cd ios e depois execute pod install para instalar todas as dependências para o iOS.

---

## 🔧 Utilizando a fake API

Antes de tudo, para que você tenha os dados para exibir em tela, existe um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, está instalado no package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para uma rota /products. Para executar esse servidor você pode executar o seguinte comando:

```bash
 yarn json-server server.json -p 3333
```

---

Desenvolvido 💙 por Pedro Oliveira

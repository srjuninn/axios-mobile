
# 🎬 App de Filmes com React Native

Este projeto é um aplicativo simples feito em **React Native**, que consome dados de uma API de filmes utilizando apenas **Axios** e **JavaScript básico**.  
A ideia é mostrar como realizar um **fetch simples** de dados e renderizar os resultados na tela.

---

## 🚀 Tecnologias utilizadas
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Axios](https://axios-http.com/)

---

## 📂 Estrutura do projeto
- `src/services/api.js` → configuração do Axios com a baseURL da API de filmes (TVMaze).
- `src/styles/globalStyles.js` → estilos globais do app.
- `App.js` → componente principal que:
  - Possui um campo de busca (`TextInput`).
  - Faz requisições à API usando Axios.
  - Renderiza os resultados em cards com imagem, título e link.

---

## 🔧 Como rodar o projeto
1. Clone este repositório:
   ```bash
    https://github.com/srjuninn/axios-mobile.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o app:
   ```bash
   npx expo start
   ```

---

## 📡 API utilizada
O app consome dados da API pública [TVMaze](https://www.tvmaze.com/api), que retorna informações sobre séries e filmes.

Exemplo de requisição:
```
https://api.tvmaze.com/search/shows?q=batman
```

---

## 🎯 Objetivo
O foco deste projeto é **aprender e demonstrar**:
- Como configurar o Axios em um projeto React Native.
- Como fazer requisições simples a uma API.
- Como renderizar dados dinamicamente na interface.

---

## 📸 Resultado esperado
- Campo de busca para digitar o nome de um filme/série.
- Lista de resultados com imagem, título e link.

---

## 📌 Observação
Este projeto não utiliza Redux, Context API ou bibliotecas avançadas.  
A ideia é manter tudo **simples e direto**, apenas com **Axios + JS básico** para entender o fluxo de consumo de APIs.

---

## Author

Feito com carinho pelo [Ryan Silva](https://github.com/srjuninn) ❤️
# 🐶 Fatos Aleatórios sobre Cachorros

Este é um projeto simples de front-end que utiliza **Ajax com fetch** para consumir uma **API pública de fatos sobre cães**.

## 📋 Descrição

A página exibe fatos curiosos e aleatórios sobre cachorros, retornados por uma API externa. O usuário pode escolher quantos fatos deseja visualizar, e o conteúdo é carregado dinamicamente na própria página, sem recarregamento.

## 🚀 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Fetch API (Ajax)**

## 🔗 API Utilizada

Este projeto consome a API pública:
```
https://dogapi.dog/api/facts
```

Essa API retorna fatos aleatórios em formato **JSON**, e é acessível diretamente do navegador pois **suporta CORS**.

## ⚙️ Como funciona

- O usuário informa um número (quantidade de fatos).
- A aplicação envia uma **requisição HTTP do tipo GET** utilizando `fetch()` (Ajax moderno).
- Os dados são recebidos no formato JSON.
- Os fatos são extraídos e exibidos dinamicamente na página com JavaScript.

## 🧪 Como executar

1. Clone o repositório:
   ```bash
   git clone https://[ithub.com/Isaisabelabela/DogFacts]
   ```

2. Abra o arquivo `index.html` no seu navegador.

3. Digite um número e clique em **Buscar Fatos** para ver os resultados.

## ✅ Benefícios do uso de Ajax com Fetch

- Permite carregamento de conteúdo **sem recarregar a página**.
- Facilita o consumo de APIs REST externas.
- Uso mais limpo e moderno comparado ao XMLHttpRequest.
- Ideal para interações rápidas e dinâmicas com o usuário.


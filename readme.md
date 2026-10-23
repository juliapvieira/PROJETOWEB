# 📚 API de Livros

A API de Livros é um projeto desenvolvido com **Node.js e Express** que permite consultar capas e imagens de diferentes gêneros literários.  
É possível sortear uma imagem aleatória ou buscar uma imagem de acordo com o gênero escolhido, por meio de uma interface simples e interativa.

## 🚀 Como executar o projeto

### 1. Instale as dependências

Abra o terminal na pasta do projeto e execute:

```bash
npm install

### 2. Inicie o servidor

```bash
node server.js
```

O servidor será iniciado em `http://localhost:3000`.

### 3. Abra a interface

Abra o arquivo `index.html` no navegador para utilizar a aplicação. Mantenha o servidor ligado enquanto estiver usando o site.

## 🔗 Rotas da API

| Método | Rota | Descrição |
|---|---|---|
| GET | `/api/livros/aleatorio` | Retorna uma imagem aleatória de qualquer esporte cadastrado. |
| GET | `/api/livros/:nome` | Retorna uma imagem aleatória da categoria informada. |

### Exemplos de requisições

- `http://localhost:3000/api/livros/aleatorio`
- `http://localhost:3000/api/livros/suspense`
- `http://localhost:3000/api/livros/romance`

Se uma categoria não existir, a API retorna o status HTTP `404` com uma mensagem de erro.

## ⚽ Categorias disponíveis

- romance
- infantil
- terror
- suspense

Cada categoria deve possuir três imagens `.jpg` na pasta correspondente dentro de `data/fotos/`.

## 🛠️ Tecnologias utilizadas

- Node.js
- Express
- CORS
- HTML5
- CSS3
- JavaScript
- JSON

## 📸 Prints do projeto

### 1. Imagem aleatória
![Print 1](img/print1.jpg)

### 2. Busca por categoria
![Print 2 - Busca por categoria](img/print2.jpg)

### 3. Mensagem de erro
![Print 3 - Erro de categoria](img/print3.jpg)

## Autora

**Nome completo:** Júlia Pardim Vieira
**Turma:** DSI1-SESI
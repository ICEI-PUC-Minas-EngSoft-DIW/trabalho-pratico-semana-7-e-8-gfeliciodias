# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Gabriel Felicio Dias  
- Matricula: 815710
- Proposta de projeto escolhida: Loja de roupas
- Breve descrição sobre seu projeto: Tenho uma loja de roupa e vou utilizar esse projeto para criar o site 

## Print da Home-Page

<img  src"https://drive.google.com/drive/folders/1ZTWhr2gQnXn2IkeiF9Xv2RlNJmZyu2si?usp=sharing" alt"">

## Print da página de detalhes do item

<img  src"https://drive.google.com/drive/folders/1ZTWhr2gQnXn2IkeiF9Xv2RlNJmZyu2si?usp=sharing" alt"">

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const dados = [
      {
      "id": 1,
      "titulo": "Camisa Ansiedade",
      "descricao": "Camisa que retrata sinais de ansiedade, e como sair da zona de conforto é necessária.",
      "conteudo": "Camisa preta com a escrita ansiedade na frente no peito com efeito borrado, na parte de tras um fantasma gritando com a frase 'Your confort zone will kil you'.",
      "categoria": "Camisa",
      "autor": "Gabriel Felicio",
      "data": "2025-002-01",
      "imagem": "https://i.pinimg.com/1200x/4a/c0/ac/4ac0ac76bcb204067296a7fc3d6a85a8.jpg"
    },
]
```
<div align=center>
  <img src="https://i.imgur.com/cVAsZfL.png" alt="Logo Ignite" width="200px">
</div>

#

![App Screenshot](https://i.imgur.com/j3qq298.png)

## Sobre
O quarto desafio do Ignite consiste em implementar um carrinho no projeto, com a opção de adicionar e remover os itens antes de prosseguir ao checkout.

A versão 2.0 continuará a utilizar os dados da API do Stripe para buscar os itens existentes, e controlará, através da sua aplicação, o número de itens que a pessoa deseja comprar.

## Novas Futures
- Adicionar produto no carrinho
- Finalizar compra pelo carrinho
- Realizar o checkout via stripe

## Stack
- Next.JS
- Typescript
- Stitches
- Stripe

## Clonando o Projeto

1. Clonar o repositório, instalar as dependências
```
yarn / npm install
```

2. Subir o projeto
```
yarn dev
```

3. Para realizar a compra, utilizar o número de cartão
```
4242 4242 4242 4242
```
OBS: A data de validade do cartão Fake precisar ter uma data posterior a atual e qualquer número de CVV.

<hr>
Só lembrando que voce vai precisar ter uma conta configurada no Stipe, inserir essas informações no arquivo .env.local e ter alguns podutos cadastrados no Stripe

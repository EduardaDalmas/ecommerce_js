# ecommerce_js

ecommerce js com cypress

1. npm init
2. npm install --save-dev cypress
3. npx cypress open

Escrever feature em linguagem Gherkin
Rodar no terminal: npm cypress open
Rodar no terminal: yarn run cypress open

Feature:
#language: pt

Funcionalidade: fazer uma compra na saucedemo

    Contexto: acessar a página para o teste
        Dado que acesso a página da saucedemo

    Cenário: acessar a página da saucedemo e fazer uma busca
        Dado que eu efetuar uma pesquisa no site
        Quando eu clicar no botão de pesquisar
        Então devo visualizar os resultados da pesquisa
        Então devo selecionar o produto
        Então devo clicar no botão de Adicionar ao carrinho
        Então devo clicar no carrinho
        Então devo verificar se o produto foi adicionado corretamente ao carrinho
        Então devo verificar se o preço total está correto
        Então devo fechar o pedido no botão de checkout
        Então devo inserir meu nome
        Então devo inserir meu sobrenome
        Então devo inserir meu codigo postal
        Então devo devo finalizar minha compra
        Então devo verificar o histórico de pedido

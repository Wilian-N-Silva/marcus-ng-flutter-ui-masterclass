## [EN]

# Project Overview: Budget App UI

"Our budget app will teach us how to code and display visualizations of our Data. We will learn how to create a bar chart combining different widgets and we will also learn how to build our own custom painter to create a real progress bar.

The first screen has a bar chart of our weekly expenses and divides our speding up into categories.

The color of the bar for each category changes based on how much money we have reamaining.

In our category screen we can view our remaning amount of money and expense."

# Data and Models

Among the initial files made available by instructor Marcus NG, we will have:

> <b>expense_model.dart</b>
>
>   Contains the "Expense" class, in which the attributes include:
>   - name (String)
>   - cost (double)

> <b>category_model.dart</b>
>
>   Responsible for the "Category" class, it contains the following attributes
>   - address (String)
>   - maxAmount (double)
>   - menu (List\<Expense>)

> <b>data.dart</b>
>
>   The data.dart file is ordered as follows:
>   - The first variable is called "rand", wich instance Random;
>   - Next we declare a list called "weeklySpending" and this is going to populate the data inside weekly spending bar graph.
>   - Creation of "_generateExpenses" function wich return a list of "Expense"
>   - List of "Category"

## [PT-BR]

# Visão Geral do Projeto: Interface do Aplicativo de Despesas

"Nosso aplicativo de despesas nos ensinará como desenvolver e exibir visualizações de nossos dados. Aprenderemos como criar um gráfico em barra, combinando diferentes widgets que também aprenderemos a construir nosso próprio custom painter, para criar barras de progresso reais.

A primeira tela terá gráficos em barras de nossas despesas semanais e dividirá em categorias.

A coloração das barras de cada categoria, muda de acordo com a quantidade de dinheiro que está disponível.

Na nossa tela de categoria, podemos visualizar quanto de dinheiro há disponível e gastos."

# Dados e Models

Dentre os arquivos iniciais disponibilizados pelo instrutor Marcus NG, teremos:

> <b>expense_model.dart</b>
>
>   Contem a classe "Expense" que dentre os atributos, contém:
>   - name (String)
>   - cost (double)

> <b>category_model.dart</b>
>
>   Responsável pela classe "Category", mantém como atributos:
>   - address (String)
>   - maxAmount (double)
>   - menu (List\<Expense>)

> <b>data.dart</b>
>
>   O arquivo data.dart segue a seguinte ordem:
>   - A primeira variável é chamada de "rand", que instancia Random;
>   - A seguir, declaramos uma list chamada "weeklySpending"  e irá popular os dados dentro do gráfico de gastos semanais.
>   - Criação da função "_generateExpenses" que retorna uma lista de "Expense"
>   - Lista de "Categoria"
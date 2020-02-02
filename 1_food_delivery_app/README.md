## [EN]

# Project Overview: Food Delivery App UI

"Our food delivery app will provide us with a great foundation to build apps that rely on list views and grid views.

We will learn how to work with text fields, stacks and create our own list tiles.

The first screen we'll create is our home screen which displays our recent orders and nearby restaurants.

The next screen is our restaurant screen where we will display information about the restaurant and the restaurant's menu items.

Our final screen is the cart screen which includes quantity selectors and a bottom sheet."

# Data and Models

Among the initial files made available by instructor Marcus NG, we will have:

> <b>food.dart</b>
>
>   Contains the "Food" class, in which the attributes include:
>   - imageUrl (String) - Contains the path of the images located in assets/images
>   - name (String)
>   - price (double)

> <b>restaurant.dart</b>
>
>   Responsible for the "Restaurant" class, it contains the following attributes
>   - imageUrl (String) - Contains the path of the images located in assets/images
>   - name (String)
>   - address (String)
>   - rating (int)
>   - menu (List\<Food>)

> <b>user.dart</b>
>
>   Responsible for the "User" class, it contains the following attributes:
>   - name (String)
>   - orders (List\<Order>)
>   - cart (List\<Order>)

> <b>order.dart</b>
>
>   In the order.dart file, we have the class "Order" containing the attributes:
>   - restaurant (Restaurant)
>   - food (Food)
>   - date (String)
>   - quantity (int)

> <b>data.dart</b>
>
>   The data.dart file is ordered as follows:
>   - Instances of the "Food" class, defining different types of products
>   -  Instances of the class "Restaurant", where the data of the restaurants and a list of products that were previously instated are assigned
>   - Then the class "User" is instantiated, taking as attributes the class "Order" which will list the recent orders and the order cart by the class "Cart".



## [PT-BR]

# Visão Geral do Projeto: Interface do Aplicativo de Entrega de Comida

"Nosso aplicativo de entrega de comida nos dará grande fundamento para construir aplicativos que dependem de visualização em lista ou grade.

Nós aprenderemos como trabalhar com campos de textos, empilhamento e criar nossos próprios 'list tiles'.

A primeira tela, criaremos nossa página inicial que mostrará os pedidos recentes e restaurantes próximos.

Na próxima tela, teremos a tela do resturante onde mostraremos informação sobre o restaurante e itens do cardápio.

Nossa tela final será o carrinho que incluirá seletores de quantidade e menu inferior."

# Dados e "Models"

Dentre os arquivos iniciais disponibilizados pelo instrutor Marcus NG, teremos:

> <b>food.dart</b>
>
>   Contém a classe "Food", no qual comporta os atributos:
>   - imageUrl (String) - Comporta o caminho das imagens localizadas em assets/images
>   - name (String)
>   - price (double)

> <b>restaurant.dart</b>
>
>   Comportando a classe "Restaurant" que contém os seguintes atributos:
>   - imageUrl (String) - Comporta o caminho das imagens localizadas em assets/images
>   - name (String)
>   - address (String)
>   - rating (int)
>   - menu (List\<Food>)

> <b>user.dart</b>
>
>   Responsável pela classe "User", ela conta com os atributos:
>   - name (String)
>   - orders (List\<Order>)
>   - cart (List\<Order>)

> <b>order.dart</b>
>
>   No arquivo order.dart, temos a classe "Order" contendo os atributos:
>   - restaurant (Restaurant)
>   - food (Food)
>   - date (String)
>   - quantity (int)

> <b>data.dart</b>
>
>   O arquivo data.dart é ordenado da seguinte forma:
>   - Instâncias da classe "Food", definindo diferentes tipos de produtos
>   -  Instâncias da classe "Restaurant", onde são atribuídos os dados dos restaurantes e uma lista de produtos que foram anteriormente instânciados
>   - Em seguida a classe "User" é instanciada, levando como atributos a classe "Order" que listará os pedidos recentes e o carrinho de pedidos pela classe "Cart".4
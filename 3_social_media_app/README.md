## [EN]

# Project Overview: Social Media App UI

"Our social media app will teach us how to use a variety of widgets like tab bars, side menu and custom clippers. All which are popular in social media apps today.

We will learn how to code our own custom clippers to shape images and how to add animations to our post scrolling to make our app come to life.

The first screen we will create is our log in screen for our users.

The next screen is our home screen where we will display the users that we're following and the posts in our feed.

Then we will add a side menu to navigate to the profile screen which displays information about our current user"

# Data and Models

Among the initial files made available by instructor Marcus NG, we will have:

> <b>post_model.dart</b>
>
>   Responsible for the "Post" class, it contains the following attributes:
>   - imageUrl (String)
>   - author (User)
>   - title (String)
>   - location (String)
>   - likes (int)
>   - comments (int)

> <b>user_model.dart</b>
>
>   Responsible for the "User" class, it contains the following attributes
>   - profileImageUrl (String)
>   - backgroundImageUrl (String)
>   - name (String)
>   - following (int)
>   - followers (int)
>   - posts (List\<Post>)
>   - favorites (List\<Post>)

> <b>data.dart</b>
>
>   - List of posts previously instantiated
>   - List of users with profileImageUrl
>   - List of current user posts
>   - List of current user favorites posts
>   - Current user data


## [PT-BR]

# Visão Geral do Projeto: Interface do Aplicativo de Despesas

"Nosso aplicativo de mídia social nos ensinará como usar uma variedade de widgets como abas, menu lateral e "clippers" customizados. Todos eles são populares em aplicativos de mídia social.

Aprenderemos como codificar nossos próprios "clippers" customizados para definir formatos de imagens e como adicionar animações em nossa rolagem de postagens para dar vida ao nosso app.

A primeira tela que criaremos será a tela de login para nossos usuários.

A próxima tela será nossa tela inicial que mostrará os usuários que estamos seguindo e as postagens em nosso feed.

Então, adicionaremos um menu lateral para navegarmos até a tela de perfil, que mostrará informações sobre o usuário."

# Data and Models

Dentre os arquivos iniciais disponibilizados pelo instrutor Marcus NG, teremos:

> <b>post_model.dart</b>
>
>   Contem a classe "Post" que dentre os atributos, contém os seguintes atributos:
>   - imageUrl (String)
>   - author (User)
>   - title (String)
>   - location (String)
>   - likes (int)
>   - comments (int)

> <b>user_model.dart</b>
>
>   Contem a classe "User" que dentre os atributos, contém os seguintes atributos:
>   - profileImageUrl (String)
>   - backgroundImageUrl (String)
>   - name (String)
>   - following (int)
>   - followers (int)
>   - posts (List\<Post>)
>   - favorites (List\<Post>)

> <b>data.dart</b>
>
>   - Lista de postagens previamente instanciados
>   - List de usuários com profileImageUrl (Caminho da imagem de perfil)
>   - List das postagens do usuário atual
>   - List das postagens favoritas do usuário atual
>   - Dados do usuário atual
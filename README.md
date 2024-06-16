# Home Chef 🍲🍷🧑‍🍳
##### PT.BR 🇧🇷
Esse é um projeto colaborativo de desenvolvimento front-end do **Home Chef**, um aplicativo de receitas de comidas e bebidas. <br>
Nele, é possível acessar receitas de inúmeras formas: através de filtros, de pesquisa por nome ou através de categorias. Além disso, é possível acessar o passo-a-passo da receita à medida que você a executa. Após concluída, essa receita fica guardada em um coleção pessoal. No Home Chef, você também pode favoritar receitas para fazer mais tarde. <br><br>
Além de mim, participaram desse projeto: **[Lina Hsu](https://github.com/linahsu)**, **[Fábio Lessa](https://github.com/fblessa)**, **[Emilly Alves](https://github.com/ellyalvescosta)** e **[Eudes Andrade](https://github.com/andradeeudes)**. <br>
Afora outros requisitos do projeto, fiquei responsável também pela estilização do aplicativo, que me desafiei a fazer em CSS puro! 🙂

##### Tecnologias utilizadas:
- Test-driven development (<i>TDD</i>)
- React.js + Vite
- TypeScript
- Redux
- CSS

## 🖼️ Imagens
![Tela de login](https://github.com/bran-do/home-chef/assets/131308486/25183d8e-6711-4490-8f5a-0b6f515e89b9)
![Receitas de bebidas](https://github.com/bran-do/home-chef/assets/131308486/65fa8305-502e-40ea-b6dd-9c89718e43d4)
![Receitas de comidas](https://github.com/bran-do/home-chef/assets/131308486/ad8107d5-f5b7-429b-91f6-cfb804fd1862)
![Uma receita de Crumble](https://github.com/bran-do/home-chef/assets/131308486/7dcf65eb-b51b-4b64-b59b-2e13e5ab1caf)
![Receitas favoritas](https://github.com/bran-do/home-chef/assets/131308486/cf1a6b34-9aa7-49c0-ac6d-b8abe5d5fdf8)
![Perfil pessoal](https://github.com/bran-do/home-chef/assets/131308486/d1c3fca2-2380-4de1-9ce8-2cdd5b2cda21)






## ⚙️ Acessando a aplicação
##### 1. Clone o repositório e crie sua branch
- Rode o comando <code>git clone git<span>@</span>github.com:bran-do/home-chef.git</code> para clonar o projeto para sua máquina.
- Crie uma branch sua a partir da branch <code>main</code> com o comando <code>git checkout -b <i>sua-branch</i></code>.
##### 2. Instale as dependências e inicialize a aplicação localmente
- Com a branch criada, instale as dependência do projeto através do comando <code>npm install</code>.
- Agora, é possível inicializar a aplicação com o comando <code>npm run start</code>.
##### 3. Acesse a aplicação no navegador
- O Vite irá determinar uma porta local para rodar a aplicação (geralmente é a porta <code>3001</code>).
- Acesse no navegador o endereço <code>localhost:<i>porta</i></code> (ex: <code>localhost:3001</code>).

<br>
<details>
  <summary>Requisitos do desenvolvimento</summary>
  
    1 – Desenvolva os testes unitários de maneira que a cobertura seja de, no mínimo, 90%
    
    2 – Crie todos os elementos que devem respeitar os atributos descritos no protótipo para a tela de login
    
    3 – Desenvolva a tela de maneira que a pessoa consiga escrever seu e-mail no input de email e sua senha no input de senha
    
    4 – Desenvolva a tela de maneira que o formulário só seja válido após o preenchimento de um e-mail válido e de uma senha com mais de 6 caracteres
    
    5 – Após a submissão do formulário, salve no localStorage o e-mail da pessoa usuária na chave user
    
    6 – Redirecione a pessoa usuária para a tela principal de receitas de comidas após a submissão e validação com sucesso do login
    
    7 – Implemente o header de acordo com a necessidade de cada tela
    
    8 – Redirecione a pessoa usuária para a tela de perfil ao clicar no botão de perfil
    
    9 – Desenvolva o botão de busca que, ao ser clicado, permita a visualização da barra de busca ou a esconda
    
    10 – Implemente os elementos da barra de busca respeitando os atributos descritos no protótipo
    
    11 – Implemente três radio buttons na barra de busca: Ingredient, Name e First letter
    
    12 – Busque na API de comidas caso a pessoa esteja na página de comidas e na API de bebidas caso a pessoa esteja na de bebidas
    
    13 – Redirecione a pessoa usuária para a tela de detalhes da receita caso apenas uma receita seja encontrada (o ID da receita deve constar na URL)
    
    14 – Caso a busca retorne mais de uma receita, renderize as 12 primeiras encontradas e exiba a imagem e o nome de cada uma delas
    
    15 – Exiba um alert caso nenhuma receita seja encontrada
    
    16 – Implemente o menu inferior posicionando-o de forma fixa e contendo dois ícones: um para comidas e outro para bebidas
    
    17 – Exiba o menu inferior apenas nas telas indicadas pelo protótipo
    
    18 - Redirecione a pessoa usuária para a tela correta ao clicar em cada ícone no menu inferior
    
    19 – Carregue as 12 primeiras receitas de comidas ou bebidas, uma em cada card
    
    20 - Implemente os botões de categoria para serem utilizados como filtro
    
    21 – Implemente o filtro das receitas por meio da API ao clicar no filtro de categoria
    
    22 – Implemente o filtro como um toggle, o qual, se for selecionado novamente, fará o app retornar as receitas sem nenhum filtro
    
    23 – Redirecione a pessoa usuária para a tela de detalhes quando ela clicar no card (a rota da tela deve mudar e sua URL deve conter o ID da receita)
    
    24 – Realize uma request para a API passando o ID da receita que deve estar disponível nos parâmetros da URL
    
    25 – Desenvolva a tela de modo que ela contenha uma imagem da receita, um título, a categoria da receita (em caso de comidas) e se é ou não alcoólica (em caso de bebidas), uma lista de ingredientes (com as quantidades e instruções necessárias), um vídeo do YouTube incorporado e recomendações
    
    26 – Implemente as recomendações (para receitas de comida, a recomendação deverá ser bebida; já para as receitas de bebida, a recomendação deverá ser comida)
    
    27 – Implemente os 6 cards de recomendação, mostrando apenas 2 deles (o scroll é horizontal, similar a um carousel)
    
    28 – Desenvolva um botão de nome "Start Recipe", que deve ficar fixo na parte de baixo da tela o tempo todo
    
    29 – Implemente a solução de forma que, caso a receita já tenha sido feita, o botão "Start Recipe" desapareça
    
    30 – Implemente a solução de modo que, caso a receita tenha sido iniciada mas não finalizada, o texto do botão deve ser "Continue Recipe"
    
    31 – Redirecione a pessoa usuária caso o botão Start Recipe seja clicado (nesse caso, a rota deve mudar para a tela de receita em progresso)
    
    32 – Implemente um botão de compartilhar e um de favoritar a receita
    
    33 – Implemente a solução de forma que, ao clicar no botão de compartilhar, o link de detalhes da receita seja copiado para o clipboard e uma mensagem avisando que ele foi copiado apareça na tela em uma tag HTML
    
    34 – Salve as receitas favoritas no localStorage na chave favoriteRecipes
    
    35 – Implemente o ícone do coração (favorito) de modo que ele fique preenchido caso a receita esteja favoritada e vazio caso contrário
    
    36 – Implemente a lógica no botão de favoritar de modo que, caso ele seja clicado, o ícone de coração mude seu estado atual e, caso esteja preenchido, mude para vazio e vice-versa
    1 – Desenvolva os testes unitários de maneira que a cobertura seja de, no mínimo, 90%
    
    2 – Crie todos os elementos que devem respeitar os atributos descritos no protótipo para a tela de login
    
    3 – Desenvolva a tela de maneira que a pessoa consiga escrever seu e-mail no input de email e sua senha no input de senha
    
    4 – Desenvolva a tela de maneira que o formulário só seja válido após o preenchimento de um e-mail válido e de uma senha com mais de 6 caracteres
    
    5 – Após a submissão do formulário, salve no localStorage o e-mail da pessoa usuária na chave user
    
    6 – Redirecione a pessoa usuária para a tela principal de receitas de comidas após a submissão e validação com sucesso do login
    
    7 – Implemente o header de acordo com a necessidade de cada tela
    
    8 – Redirecione a pessoa usuária para a tela de perfil ao clicar no botão de perfil
    
    9 – Desenvolva o botão de busca que, ao ser clicado, permita a visualização da barra de busca ou a esconda
    
    10 – Implemente os elementos da barra de busca respeitando os atributos descritos no protótipo
    
    11 – Implemente três radio buttons na barra de busca: Ingredient, Name e First letter
    
    12 – Busque na API de comidas caso a pessoa esteja na página de comidas e na API de bebidas caso a pessoa esteja na de bebidas
    
    13 – Redirecione a pessoa usuária para a tela de detalhes da receita caso apenas uma receita seja encontrada (o ID da receita deve constar na URL)
    
    14 – Caso a busca retorne mais de uma receita, renderize as 12 primeiras encontradas e exiba a imagem e o nome de cada uma delas
    
    15 – Exiba um alert caso nenhuma receita seja encontrada
    
    16 – Implemente o menu inferior posicionando-o de forma fixa e contendo dois ícones: um para comidas e outro para bebidas
    
    17 – Exiba o menu inferior apenas nas telas indicadas pelo protótipo
    
    18 - Redirecione a pessoa usuária para a tela correta ao clicar em cada ícone no menu inferior
    
    19 – Carregue as 12 primeiras receitas de comidas ou bebidas, uma em cada card
    
    20 - Implemente os botões de categoria para serem utilizados como filtro
    
    21 – Implemente o filtro das receitas por meio da API ao clicar no filtro de categoria
    
    22 – Implemente o filtro como um toggle, o qual, se for selecionado novamente, fará o app retornar as receitas sem nenhum filtro
    
    23 – Redirecione a pessoa usuária para a tela de detalhes quando ela clicar no card (a rota da tela deve mudar e sua URL deve conter o ID da receita)
    
    24 – Realize uma request para a API passando o ID da receita que deve estar disponível nos parâmetros da URL
    
    25 – Desenvolva a tela de modo que ela contenha uma imagem da receita, um título, a categoria da receita (em caso de comidas) e se é ou não alcoólica (em caso de bebidas), uma lista de ingredientes (com as quantidades e instruções necessárias), um vídeo do YouTube incorporado e recomendações
    
    26 – Implemente as recomendações (para receitas de comida, a recomendação deverá ser bebida; já para as receitas de bebida, a recomendação deverá ser comida)
    
    27 – Implemente os 6 cards de recomendação, mostrando apenas 2 deles (o scroll é horizontal, similar a um carousel)
    
    28 – Desenvolva um botão de nome "Start Recipe", que deve ficar fixo na parte de baixo da tela o tempo todo
    
    29 – Implemente a solução de forma que, caso a receita já tenha sido feita, o botão "Start Recipe" desapareça
    
    30 – Implemente a solução de modo que, caso a receita tenha sido iniciada mas não finalizada, o texto do botão deve ser "Continue Recipe"
    
    31 – Redirecione a pessoa usuária caso o botão Start Recipe seja clicado (nesse caso, a rota deve mudar para a tela de receita em progresso)
    
    32 – Implemente um botão de compartilhar e um de favoritar a receita
    61 – Redirecione a pessoa usuária de modo que, ao clicar no botão de Favorite Recipes, a rota mude para a tela de receitas favoritas
    37 – Desenvolva a tela de modo que ela contenha uma imagem da receita, um título, a categoria (em caso de comidas) e se é ou não alcoólico (em caso de bebidas), uma lista de ingredientes (com as quantidades e instruções necessárias)
    
    38 – Desenvolva um checkbox para cada item da lista de ingredientes
    
    39 - Implemente uma lógica que ao clicar no checkbox de um ingrediente, o nome dele deve ser "riscado" da lista
    
    40 - Salve o estado do progresso, que deve ser mantido caso a pessoa atualize a página ou volte para a mesma receita
    
    41 - Desenvolva a lógica de favoritar e compartilhar (a lógica da tela de detalhes de uma receita se aplica aqui)
    
    42 - Implemente a solução de modo que o botão de finalizar receita (Finish Recipe) só esteja habilitado quando todos os ingredientes estiverem "checkados" (marcados)
    
    43 - Redirecione a pessoa usuária após ela clicar no botão de finalizar receita (Finish Recipe) para a página de receitas feitas, cuja rota deve ser /done-recipes
    
    44 – Implemente os elementos da tela de receitas feitas respeitando os atributos descritos no protótipo
    
    45 – Desenvolva a tela de modo que, caso a receita do card seja uma comida, ela apresente: foto da receita, nome, categoria, nacionalidade, data em que a pessoa fez a receita, duas primeiras tags retornadas pela API e botão de compartilhar
    
    46 – Desenvolva a tela de maneira que, caso a receita do card seja uma bebida, ela apresente: foto da receita, nome, se é alcoólica, data em que a pessoa fez a receita e botão de compartilhar
    
    47 – Desenvolva a solução de modo que o botão de compartilhar copie a URL da tela de detalhes da receita para o clipboard
    
    48 – Implemente 2 botões que filtram as receitas por comida ou bebida e um terceiro que remove todos os filtros
    
    49 – Redirecione a pessoa usuária para a tela de detalhes da receita caso seja clicado na foto ou no nome da receita
    
    50 – Implemente os elementos da tela de receitas favoritas (cumulativo com os atributos em comum com a tela de receitas feitas) respeitando os atributos descritos no protótipo
    
    51 – Desenvolva a tela de modo que, caso a receita do card seja uma comida, ela apresente: foto da receita, nome, categoria, nacionalidade, botão de compartilhar e botão de desfavoritar
    
    52 – Desenvolva a tela de modo que, caso a receita do card seja uma bebida, ela apresente: foto da receita, nome, se é alcoólica ou não, botão de compartilhar e botão de desfavoritar
    
    53 – Desenvolva a solução de modo que o botão de compartilhar copie a URL da tela de detalhes da receita para o clipboard
    
    54 – Desenvolva a solução de modo que o botão de desfavoritar remova a receita da lista de receitas favoritas do localStorage e da tela
    
    55 – Implemente dois botões que filtrem as receitas por comida ou bebida e um terceiro que remova todos os filtros
    
    56 – Redirecione a pessoa usuária quando ela clicar na foto ou no nome da receita (nesse caso, a rota deve mudar para a tela de detalhes daquela receit
    
    57 – Implemente os elementos da tela de perfil respeitando os atributos descritos no protótipo
    
    58 – Implemente a solução de maneira que o e-mail da pessoa usuária esteja visível
    
    59 – Implemente três botões: um de nome Done Recipes, um de nome Favorite Recipes e um de nome Logout
    
    60 – Redirecione a pessoa usuária de modo que, ao clicar no botão de `Done Recipes, a rota mude para a tela de receitas feitas
    
    61 – Redirecione a pessoa usuária de modo que, ao clicar no botão de Favorite Recipes, a rota mude para a tela de receitas favoritas

    62 – Redirecione a pessoa usuária de modo que, ao clicar no botão Logout, o localStorage seja limpo e a rota mude para a tela de login
  
</details>
<br>
<hr>

##### EN 🇬🇧/🇺🇸
This is a colaborative front-end development project of **Home Chef**, a food and drink recipe app. <br>
Here you can access recipes through many ways: filtes, name search or categories. You can also access a step-by-step process of any recipe to help you in real time. Once a recipe is finished, it is added to a personal collection. On Home Chef, besides, you can save recipes to execute them later by favoriting them. <br><br>
Alongside me, this project was developed by: **[Lina Hsu](https://github.com/linahsu)**, **[Fábio Lessa](https://github.com/fblessa)**, **[Emilly Alves](https://github.com/ellyalvescosta)** e **[Eudes Andrade](https://github.com/andradeeudes)**. <br>
I was responsible, among many other things, for the app stylization, in which I challenged myself to do in vanilla CSS! 🙂

##### Technology tools used:
- Test-driven development (<i>TDD</i>)
- React.js + Vite
- TypeScript
- ContextAPI
- CSS

### ⚙️ Accessing the application
##### 1. Clone this repository
- Run <code>git clone git<span>@</span>github.com:bran-do/tempinho-bom.git</code> on your terminal.
- Create a new branch from <code>main</code> with <code>git checkout -b <i>your-branch</i></code>.
##### 2. Install project dependencies and run application locally
- After creating a new branch, you must install project dependencies through <code>npm install</code>.
- Now, you can initialize the application locally through <code>npm run start</code>.
##### 3. Access application on browser
- Vite will choose a local port to run the application (usually it's port <code>3001</code>).
- Access <code>localhost:<i>port</i></code> in your browser (e.g.: <code>localhost:3001</code>). 

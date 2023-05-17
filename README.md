# lista de compras🛒
 _Este é um projeto feito em aula no Android Studio que implementa um exemplo de recycler view, um layout que permite o cadastro de produtos e a sua visualização. O cadastro é feito e mostrado no [firebase](https://firebase.google.com/?hl=pt-br) através do [realtime database](https://firebase.google.com/docs/database?hl=pt-br)._
 
## ⚙️Funcionalidades:
O aplicativo implementa um exemplo simples de recycler view com uma tela principal (`activity_main.xml`) no qual ao clicar no botão `Novo Produto`, o usuário é redirecionado para a tela de cadastro (`activity_tela_cadastro.xml`) onde consegue cadastrar um novo produto que será visualizado na tela onde estão cadastrados os produtos (`layout.xml`).

### ⭐Tela principal:
>`activity_main.xml`
- Essa tela possui um botão chamado `Novo Produto` que ao clicar, o usuário é redirecionado para a tela de cadastro (`activity_tela_cadastro.xml`).

### ✍️Tela de cadastro:
>`activity_tela_cadastro.xml`
- Essa tela consiste em três edit text, um para o usuário inserir o nome do produto e sua categoria, e um edit text do tipo number (decimal) no qual o usuário consegue inserir o preço do produto.
- Ao clicar no botão `Cadastrar`, o usuário é redirecionado para a tela onde estão cadastrados os produtos (`layout.xml`) para que então possa visualizar os produtos anteriormente cadastrados.

### 📂Tela de produtos cadastrados:
>`layout.xml`
- Essa tela contém os produtos anteriormente cadastrados na tela de cadastro (`activity_tela_cadastro.xml`), aqui o produto é visualizado com seu respectivo **nome**, **tipo** e **preço** através de um **_CardView_**.

## 🔥[Firebase](https://firebase.google.com/?hl=pt-br)
> Banco de dados utilizado nessa aplicação para cadastrar os produtos.
> 
> [Documentações do Firebase](https://firebase.google.com/docs?hl=pt-br)
> 
> [Documentação do RealTime Dataset](https://firebase.google.com/docs/database?hl=pt-br)




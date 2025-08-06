# CSS Flexbox Property

> **Este é um exercício prático para aprendermos a utilizar a propriedade Flexbox do CSS.**

#### Escrevendo o HTML (A Estrutura da Navbar)

Galera, vamos criar uma estrutúra básica para nosso cabeçalho.
Copie e cole o código abaixo, dentro da tag `body`, no seu arquivo `index.html`

##### Crie um arquivo (index.html)
```
    <header class="navbar-container">
        <div class="logo">
            <a href="#">MeuLogo</a>
        </div>
        <nav class="menu-items">
            <a href="#">Home</a>
            <a href="#">Sobre</a>
            <a href="#">Serviços</a>
            <a href="#">Contato</a>
        </nav>
    </header>
```

Logo abaixo da tag `</header>`, cole o conteúdo principal da nossa página:
```
    <main>
        <h1>Bem-vindo à Atividade Flexbox!</h1>
        <p>Use esta página para ver sua navbar em ação.</p>
    </main>
```

Agora, com o live preview do seu vscode, já é possível ver como a estrutura está ficando.

Logo após, crie um arquivo chamado `style.css`
Dentro deste arquivo colo o código abaixo. Este código ainda não tem o flex, mas servirá para dar um pouco mais de cor; deixar mais bonito o nosso cabeçalho:
```
/* Reset básico e estilos do corpo */
body {
    font-family: sans-serif;
    margin: 0;
    background-color: #f4f4f4;
}

/* Estilizando o contêiner da navbar */
.navbar-container {
    background-color: #333;
    padding: 15px;
    color: white;
}

/* Estilizando os links dentro da navbar para melhor visualização */
.navbar-container a {
    color: white;
    text-decoration: none;
    margin: 0 10px; /* Adiciona um espaço entre os links */
    font-size: 18px;
}

.logo a {
    font-weight: bold;
    font-size: 24px;
}
```

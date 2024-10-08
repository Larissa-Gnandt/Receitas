# Projeto de Receitas

Bem-vindo ao Projeto de Receitas! Este projeto consiste em um site simples de receitas, onde você pode navegar pela página inicial, visualizar uma lista de receitas e realizar o cadastro de usuários.

## Estrutura do Projeto

O projeto possui três páginas principais:

1. **Home:** A página inicial, onde o usuário é apresentado ao projeto e pode navegar pelas outras seções do site.
2. **Receitas:** Uma página que lista todas as receitas disponíveis no site.
3. **Cadastro:** Uma página onde os usuários podem se cadastrar.

### Funcionalidades

- **Navegação:** O usuário pode navegar entre as páginas através de um menu de navegação.
- **Exibição de Receitas:** Na página de receitas, o usuário pode visualizar todas as receitas disponíveis.
- **Cadastro de Usuário:** Na página de cadastro, o usuário pode se registrar criando uma conta preenchendo um formulário com informações como nome, e-mail e endereço.

## Estrutura de Arquivos

Abaixo está a estrutura básica dos arquivos do projeto:

```
/receitas
│
├── /assets
│   ├── /imagens                # Pasta para imagens
│
├── /css
│   ├── bootstrap.css           # Estilos do Bootstrap
│   ├── bootstrap.min.css.map   # Arquivo de debugging do Bootstrap
│   ├── cadastro.css            # Estilos da página "Cadastro"
│   ├── formatos.css            # Estilos globais do projeto
│   ├── home.css                # Estilos da página "Home"
│   └── receitas.css            # Estilos da página "Receitas"
│
├── /js
│   ├── bootstrap.js            # Funções dinâmicas do Bootstrap
│   ├── bootstrap.min.js.map    # Arquivo de debugging do Bootstrap
│   └── jquery.js               # Biblioteca para manipulação do DOM
│
├── cadastro.html               # Página de cadastro
├── home.html                   # Página principal (Home)
├── receitas.html               # Página de receitas
├── README.md                   # Arquivo com instruções do projeto

```

## Tecnologias Utilizadas

- **HTML:** Para estruturar o conteúdo das páginas.
- **CSS:** Para estilizar o layout e a aparência das páginas.
- **Bootstrap:** Para criar o formulário de cadastro do usuário.

## Como Usar

1. Clone este repositório para o seu ambiente local:

```
git clone git@github.com:Larissa-Gnandt/receitas.git
```

2. Navegue até o diretório do projeto:

```
cd receitas
```

3. Abra o arquivo home.html no seu navegador para visualizar a página inicial.
4. Explore as demais páginas:

- receitas.html para visualizar as receitas.
- cadastro.html para criar uma conta de usuário.

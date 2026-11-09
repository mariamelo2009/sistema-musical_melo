# sistema-musical_melo
# 🎵 Sistema Musical

## 📌 Sobre o Projeto

O **Sistema Musical** é uma aplicação web desenvolvida para organizar e gerenciar informações relacionadas a artistas e músicas.

O projeto possui uma interface simples e organizada, permitindo ao usuário acessar diferentes áreas do sistema, como cadastro de artistas, cadastro de músicas e uma biblioteca musical.

A aplicação foi desenvolvida utilizando principalmente **HTML5 e CSS3**, com páginas independentes conectadas por links de navegação.

---

## 🎯 Objetivo da Atividade

O objetivo da atividade é desenvolver uma interface de um sistema musical, aplicando conhecimentos de:

- HTML5;
- CSS3;
- Formulários;
- Campos de entrada;
- Tabelas;
- Links e navegação entre páginas;
- Organização de informações;
- Design responsivo;
- Estruturação de páginas web.

O projeto também apresenta uma estrutura preparada para uma futura integração com banco de dados e uma aplicação dinâmica.

---

## 🖥️ Funcionalidades

O sistema possui as seguintes funcionalidades:

### 🔐 Login

A página de login permite que o usuário informe seu nome de usuário e senha para acessar o sistema.

As credenciais de teste apresentadas no projeto são:

```text
Usuário: admin
Senha: 123
```

A tela possui campos obrigatórios para usuário e senha.

---

### 🏠 Menu Principal

Após o acesso, o usuário encontra o menu principal do **Sistema Musical**.

O menu apresenta opções para:

- 🎤 Gerenciar artistas;
- 🎵 Cadastrar músicas;
- 🎼 Acessar a biblioteca musical;
- 🚪 Sair do sistema.

Essas opções direcionam o usuário para as diferentes páginas do projeto.

---

### 🎤 Cadastro de Artistas

A página de cadastro de artistas permite inserir informações como:

- Nome do artista;
- Gênero musical;
- País;
- Foto do artista.

Também existe uma tabela para visualizar artistas cadastrados, com opções de edição, exclusão e acesso às músicas do artista. 

---

### 🎵 Cadastro de Músicas

A tela de cadastro de músicas permite registrar informações relacionadas às músicas.

Os campos disponíveis são:

- Artista;
- Título;
- Álbum;
- Gênero;
- Link do YouTube;
- Capa do álbum;
- Letra da música.

O campo de artista é obrigatório, assim como o título e o link do YouTube. 

Também existe uma tabela para apresentar as músicas cadastradas, mostrando informações como título, álbum, link para assistir no YouTube e ações de edição e exclusão.

---

### 🎼 Biblioteca Musical

A biblioteca permite visualizar as músicas cadastradas no sistema.

A página possui filtros para:

- Busca geral;
- Artista;
- Gênero.

Também apresenta uma tabela com:

- Capa;
- Título;
- Artista;
- Álbum;
- Gênero;
- YouTube;
- Ações.

Os filtros estão estruturados para uma futura integração com dados vindos de um banco de dados.

---

## 📁 Estrutura do Projeto

```text
📦 Sistema-Musical
│
├── 📄 index.html
├── 📄 login.html
├── 📄 cadastro_artista.html
├── 📄 cadastro_musica.html
├── 📄 listagem_musicas.html
└── 🎨 styles.css
```

### `index.html`

Página principal do sistema, contendo o menu de navegação para as principais funcionalidades.

### `login.html`

Página responsável pela interface de login do usuário.

### `cadastro_artista.html`

Página destinada ao cadastro e gerenciamento dos artistas.

### `cadastro_musica.html`

Página destinada ao cadastro das músicas e suas informações.

### `listagem_musicas.html`

Página que apresenta a biblioteca musical e os filtros de pesquisa.

### `styles.css`

Arquivo responsável pela estilização geral do sistema.

Nele são definidos elementos como:

- Cores;
- Fontes;
- Botões;
- Formulários;
- Tabelas;
- Cards;
- Espaçamentos;
- Responsividade;
- Efeitos de interação.

O arquivo também possui regras específicas para telas menores, adaptando o layout para dispositivos móveis. 

---

## 🎨 Tecnologias Utilizadas

| Tecnologia | Utilização |
|---|---|
| **HTML5** | Estrutura das páginas |
| **CSS3** | Estilização e layout |
| **Formulários HTML** | Entrada de dados |
| **Tabelas HTML** | Exibição das informações |
| **Links HTML** | Navegação entre as páginas |

---

## 📱 Responsividade

O projeto possui suporte para diferentes tamanhos de tela.

No arquivo `styles.css`, existem regras `@media` para adaptar o conteúdo em dispositivos com largura menor, modificando principalmente:

- Layout dos formulários;
- Organização dos filtros;
- Tamanho das tabelas;
- Tamanho das imagens;
- Organização dos botões;
- Cards do menu.

Assim, o sistema pode ser visualizado tanto em computadores quanto em dispositivos menores.

---

## 🔄 Navegação do Sistema

A navegação básica do projeto pode ser representada da seguinte forma:

```text
                    ┌──────────────┐
                    │    LOGIN     │
                    │  login.html  │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │ MENU PRINCIPAL│
                    │  index.html   │
                    └──────┬───────┘
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
      ┌────────────┐ ┌────────────┐ ┌─────────────┐
      │  ARTISTAS  │ │  MÚSICAS   │ │  BIBLIOTECA │
      │  Cadastro  │ │  Cadastro  │ │  Listagem   │
      └──────┬─────┘ └────────────┘ └─────────────┘
             │
             ▼
      ┌────────────┐
      │  MÚSICAS   │
      │ DO ARTISTA │
      └────────────┘
```

---

## 📝 Formulários

Os formulários utilizam diferentes tipos de campos HTML para receber informações do usuário.

Entre eles estão:

- `text` — campos de texto;
- `password` — senha;
- `url` — endereço do YouTube;
- `file` — envio de imagens;
- `select` — seleção de opções;
- `textarea` — textos maiores.

Na página de músicas, por exemplo, o campo de link do YouTube utiliza `type="url"` para representar um endereço de internet.

---

## 🚀 Como Executar o Projeto

Como o projeto é composto por arquivos HTML e CSS, é possível executá-lo localmente.

### 1. Baixe ou clone o projeto

Baixe os arquivos para o computador ou clone o repositório do GitHub.

### 2. Abra a pasta no VS Code

Abra a pasta do projeto no **Visual Studio Code**.

### 3. Execute o projeto

Abra o arquivo:

```text
login.html
```

Depois, execute-o no navegador.

A partir da tela de login, é possível acessar o restante da estrutura do sistema.

---

## 📌 Observação

Nesta versão, algumas informações apresentadas nas tabelas estão inseridas diretamente no HTML. A própria estrutura dos arquivos indica que, em uma etapa posterior, esses dados poderão ser substituídos por informações vindas de um banco de dados.

Portanto, o projeto representa principalmente a **interface e estrutura inicial do Sistema Musical**.

---

## 👨‍💻 Desenvolvedor

Projeto desenvolvido como atividade acadêmica para prática de desenvolvimento web.

---

## 📚 Conclusão

A atividade permitiu desenvolver um sistema web organizado em diferentes páginas, utilizando HTML5 para estruturar o conteúdo e CSS3 para criar o visual da aplicação.

O projeto apresenta uma estrutura de **login, gerenciamento de artistas, cadastro de músicas e biblioteca musical**, servindo como base para futuras implementações com banco de dados e funcionalidades dinâmicas.

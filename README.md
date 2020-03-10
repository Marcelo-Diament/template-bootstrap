[![WevDev](https://djament.com.br/img/placeholder-logo-120x120.png)](https://github.com/Marcelo-Diament/template-bootstrap)

# Template Bootstrap

Esse repositório foi elaborado para fins didáticos, visando demonstrar a construção de sites simples utilizando principalmente o Bootstrap. Mas atenção, não se apegue muito ao Bootstrap, é fundamental entendermos o que está acontecendo por debaixo dos panos, não só para termos maior controle sobre nosso projeto como para não dependermos de bibliotecas nem de exemplos prontos. O que vamos construir nesse repositório?

 ### Páginas Públicas
  - Header e Footer
  - Página Inicial
  - Página de Contato
  - Página de Categoria de Produtos
  - Página de Detalhe de um Produto
  - Página Institucional
  - Página de Cadastro
  - Página (ou Modal) de Log In

 ### Páginas de Acesso Restrito
  - Página de Edição de Perfil

### Páginas Administrativas
  - Página de Listagem de Usuários
  - Página de Listagem de Categorias
  - Página de Listagem de Produtos
  - Página de Listagem de Mensagens Recebidas

_Esse repositório - a princípio - engloba apenas a parte do front end (parte de interface, visual), não abrange ações relacionadas ao back end (como registro de usuários, produtos, validação de login, etc..)._


## Entendendo o Repositório

A ideia é simular a construção de um site real - de forma simples e didática. Por isso vamos dividir cada feature (recurso) em uma branch distinta. À medida que formos finalizando cada recurso, iremos abrir um Pull Request e 'mergear' a branch da feature com a master. Como é um projeto bem simples, não utilizaremos o Git Flow, apenas uma simulação. No final desse documento (readme.md), listaremos todos os recursos externos utilizados.


## Changelog
Changelog é um log de atualizações, ou seja, a cada novo merge com a master, listaremos aqui o que foi desenvolvido.

### v0.0.1
> Inclusão do arquivo README.md


## Stack | Tecnologias Utilizadas
A stack utilizada aqui é muito simples, fazendo uso apenas de:

* **HTML** (estruturação de nossos documentos)
* **CSS** (aproveitaremos ao máximo o estilo vindo do Bootstrap)
* **PHP** (de modo bem simples, sem nem ao menos realizarmos CRUD, apenas para aplicarmos o conceito de DRY)
* **JS** (a princípio, apenas através do Bootstrap, por conta do objetivo do repositório)


## Recursos Externos
Nosso repositório utiliza-se dos seguintes recursos:

* **[Bootstrap]** - Uma biblioteca de estilo (CSS) e interação (JS) carregadas através de classes e outros atributos
* **[FontAwesome]** - Uma biblioteca de ícones vetorizados carregados através de classes
* **[Dillinger]** - Uma ferramenta online para formatação de texto no formado markdown (.md)


## Requisitos

Para rodar esse repositório, você precisará apenas de recursos básicos, tais como:

- Uma IDE (um editor de textos voltado para desenvolvimento). Sugermios o uso do Visual Studio Code.
- Um servidor local (para rodar os arquivos PHP). Sugerimos o uso do xampp.


## Requisitos

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

## Links Úteis
A seguir, uma tabela com os links úteis para rodar o repositório e aprender conosco!

| Biblioteca | Download | Documentação |
| ------ | ------ | ------ |
| **[Bootstrap]** | [Acessar][BootstrapDownload] | [Ler Documentação][BootstrapDocs] |
| **[FontAwesome]** | [Acessar][FontAwesomeDownload] | [Ler Documentação][FontAwesomeDocs] |
| **[Dillinger]** | _online_ | [Ler Documentação][DillingerDocs] |
| **[Github]** | _online_ | [Ler Documentação][GithubDocs] |
| **[xampp]** | [Acessar][XamppDownload] | [Ler Documentação][XamppDocs] |
| **[VS Code]** | [Acessar][VSCodeDownload] | [Ler Documentação][VSCodeDocs] |




**Desenvolvido por**

[![Djament](https://djament.com.br/favicons/apple-touch-icon-precomposed-120x120.png)](https://djament.com.br)
**Marcelo Diament | Djament Comunicação + WebDev**

[//]: # (A seguir, os links que constam nesse documento)


   [Bootstrap]: <https://getbootstrap.com/>
   [BootstrapDownload]: <https://getbootstrap.com/docs/4.4/getting-started/download/r>
   [BootstrapDocs]: <https://getbootstrap.com/docs/4.4/getting-started/introduction/>
   [FontAwesome]: <https://fontawesome.com/>
   [FontAwesomeDownload]: <https://fontawesome.com/download>
   [FontAwesomeDocs]: <https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use>
   [Dillinger]: <https://dillinger.io/>
   [DillingerDocs]: <https://www.markdownguide.org/>
   [Github]: <https://github.com/>
   [GithubDocs]: <https://github.blog/>
   [xampp]: <https://www.apachefriends.org/pt_br/index.html>
   [xamppDownload]: <https://www.apachefriends.org/download.html>
   [xamppDocs]: <https://www.apachefriends.org/faq_windows.html>
   [VS Code]: <https://code.visualstudio.com/>
   [VSCodeDownload]: <https://code.visualstudio.com/download>
   [VSCodeDocs]: <https://code.visualstudio.com/docs>
   

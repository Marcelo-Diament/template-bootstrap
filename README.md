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
  - Página de Políticas de Privacidade
  - Página de Termos de Uso

 ### Páginas de Acesso Restrito
  - Página de Edição de Perfil
  - Página de Histórico de Pedidos

### Páginas Administrativas
  - Página de Listagem de Usuários
  - Página de Listagem de Categorias
  - Página de Listagem de Produtos
  - Página de Listagem de Mensagens Recebidas

_Esse repositório - a princípio - engloba apenas a parte do front end (parte de interface, visual), não abrange ações relacionadas ao back end (como registro de usuários, produtos, validação de login, etc..)._


## Entendendo o Repositório
A ideia é simular a construção de um site real - de forma simples e didática. Por isso vamos dividir cada feature (recurso) em uma branch distinta. À medida que formos finalizando cada recurso, iremos abrir um Pull Request e 'mergear' a branch da feature com a master. Como é um projeto bem simples, não utilizaremos o Git Flow, apenas uma simulação. No final desse documento (readme.md), listaremos todos os recursos externos utilizados.


## Stack | Tecnologias Utilizadas
A stack utilizada aqui é muito simples, fazendo uso apenas de:

* **HTML** (estruturação de nossos documentos)
* **CSS** (aproveitaremos ao máximo o estilo vindo do Bootstrap)
* **PHP** (de modo bem simples, sem nem ao menos realizarmos CRUD, apenas para aplicarmos o conceito de DRY)
* **JS** (a princípio, apenas através do Bootstrap, por conta do objetivo do repositório)


## Recursos Externos
Nosso repositório utiliza-se dos seguintes recursos e *libs* (bibliotecas):

* **[Bootstrap]** - Uma biblioteca de estilo (CSS) e interação (JS) carregadas através de classes e outros atributos
* **[FontAwesome]** - Uma biblioteca de ícones vetorizados carregados através de classes
* **[Dillinger]** - Uma ferramenta online para formatação de texto no formado markdown (.md)


## Requisitos
Para rodar esse repositório, você precisará apenas de recursos básicos, tais como:

- Uma IDE (um editor de textos voltado para desenvolvimento). Sugermios o uso do [VSCode] (ou Visual Studio Code);
- Um servidor local (para rodar os arquivos PHP). Sugerimos o uso do [xampp];
- Um terminal feito para facilitar o uso de repositórios git, o [GitBash].

Preparamos no tópico adiante uma lista com links para providenciar tudo o que precisa e poder aprofundar seus estudos.


## Links Úteis
A seguir, uma tabela com os links úteis para tirar melhor proveito do repositório

| Biblioteca | Download | Documentação |
| ------ | ------ | ------ |
| **[Bootstrap]** | [Acessar][BootstrapDownload] | [Ler Documentação][BootstrapDocs] |
| **[FontAwesome]** | [Acessar][FontAwesomeDownload] | [Ler Documentação][FontAwesomeDocs] |
| **[Dillinger]** | _online_ | [Ler Documentação][DillingerDocs] |
| **[Github]** | _online_ | [Ler Documentação][GithubDocs] |
| **[xampp]** | [Acessar][XamppDownload] | [Ler Documentação][XamppDocs] |
| **[GitBash]** | [Acessar][GitBashDownload] | [Ler Documentação][GitBashDocs] |
| **[VSCode]** | [Acessar][VSCodeDownload] | [Ler Documentação][VSCodeDocs] |


## Como utilizar esse repositório?

Após instalar os programas listados no tópico **Requisitos**, rode o seguinte comando no terminal (dentro do próprio [VSCode] ou no prompt do [GitBash] para clonar esse repositório:

```sh
$ cd ./c/xampp/htdocs
$ git clone https://github.com/Marcelo-Diament/template-bootstrap.git
$ cd template-bootstrap
```

E para atualizar o repositório:

```sh
$ cd ./c/xampp/htdocs/template-bootstrap
$ git pull origin master
```


## Changelog
Changelog é um log de atualizações, ou seja, a cada novo merge com a master, listaremos aqui o que foi desenvolvido.

### v0.0.1
> Inclusão do arquivo README.md

> Estruturação básica do projeto (arquivos e pastas)


## Dica
Para se manter à par das atualizações desse projeto, você pode 'Favoritar' e/ou 'Ficar de Olho' nas atualizações. Para isso, basta acessar o repositório e clicar em 'Star' e/ou 'Watch'.


#### **Esperamos que curta esse repositório feito para te ajudar a se tornar um desenvolvedor web! Em caso de dúvidas, entre em contato conosco - inclusive para colaborar e sugerir melhorias!**


**Desenvolvido por**

[![Djament Comunicação](https://djament.com.br/favicons/apple-touch-icon-precomposed-120x120.png)](https://djament.com.br)
**[Marcelo Diament] | [Djament Comunicação] + WebDev**

[//]: # (A seguir, os links que constam nesse documento)

   [Djament Comunicação]: <https://djament.com.br>
   [Marcelo Diament]: <https://www.linkedin.com/in/marcelodiament/>
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
   [GitBash]: <https://gitforwindows.org/>
   [GitBashDownload]: <https://gitforwindows.org/>
   [GitBashDocs]: <https://github.com/git-for-windows/git/wiki/FAQ>
   [VSCode]: <https://code.visualstudio.com/>
   [VSCodeDownload]: <https://code.visualstudio.com/download>
   [VSCodeDocs]: <https://code.visualstudio.com/docs>

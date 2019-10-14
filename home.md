<!-- TITLE: Home -->
<!-- SUBTITLE: A quick summary of Home -->

# Configurar seu Wiki com wiki.js
*Salve garera! *

Precisava de uma **Wiki** para a empresa que trabalho, na verdade pretendemos usar uma **Wiki** para documentação de algumas tarefas que temos como *RDM*, *DataSource*, *Tutoriais* e *outras coisas*.

Sem delongas, acabei encontrando o **Wiki.js**, uma plataforma wiki, sensacional e com as melhores tecnologias!

Para você ter uma idéia, eu criei essa Wiki em menos de 10 minutos, tudo em Cloud.

**Tecnologias empregadas**

* Node
* Git
* MongoDB

**Vantagens do wiki.js**

* Fácil de instalar e usar
* Ter suporte a Markdown
* Open source
* Poder gerenciar permissões de usuários e artigos
* Possuir um sistema de busca

**Mão à obra!**

## A configuração e deploy foram feitos no Heroky - Motivação: Aprender novas tecnologias

** Você vai precisar: **

1º - Criar uma conta no Heroky para deploy de sua aplicação.
2º - Ter um repositorio GitHub criado.
3º - Mais nada.

**Heroku**
Criar uma conta o  é fácil e rápido. Segue o link para cadastro: https://id.heroku.com/login

**GitHub**
Se já não tem, o que acho difícil de acontecer, mas....se ainda não tem segue o link para cadastro: https://github.com/ 

**Configuração e Instação**

1º - Acesse o repositório https://github.com/Requarks/wiki-v1
2º - Procure pelo botão **Deploy to Heroku**.

![Wiki 01](/uploads/wiki-js/wiki-01.png "Wiki 01"){.align-center}

Ou se preferir o link até o momento é esse: https://heroku.com/deploy?template=https://github.com/requarks/wiki-heroku


**Complete os seguintes campos:**
**App name:** Nome do seu wiki. Tem que ser tudo em minúsco e sem espaço e caracteres especiais.
**WIKI_ADMIN_EMAIL:** Seu e-mail.
**WIKI_GIT_BRANCH:** Branch usada no repositório.
**WIKI_GIT_PASSWORD:** Senha do Repositório GitHub (no nosso caso, porque pode ser usar GitLab e Bitbucket)
**WIKI_GIT_URL:** Url do repositório que você criou para armazenar sua Wiki.
**WIKI_HOST:** Url da sua Wiki. *Exemplo: https://minhawiki.herokuapp.com*
**WIKI_IS_PUBLIC:** true caso deseja uma Wiki publica.
**WIKI_SERVER_EMAIL:** Seu e-mail.
**WIKI_TITLE:** Título da sua Wiki.

Após preencher o formulário clique no botão **"Deploy app"**

Pronto, sua Wiki será configurada e deployada.

Acesse a url que você colocou em **WIKI_HOST:**

**Obs.:** Sua senha de admin por default é *admin123*

Espero que gostem e qualquer dúvida é só me perguntar!

acacio.am@gmail.com
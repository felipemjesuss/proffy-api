<p align="center">
   <img src="./.github/logo.png" alt="Proffy" width="280"/>
</p>

<p align="center">	
   <a href="https://www.linkedin.com/in/felipemjesuss/">
      <img alt="Felipe Martins" src="https://img.shields.io/badge/-FelipeMartins-8257E5?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/felipemjesuss/proffy-api?color=774DD6">

  <a aria-label="Completed" href="https://nextlevelweek.com/episodios/omnistack/edicao/2">
    <img src="https://img.shields.io/badge/Proffy-NLW 2.0-8257E5?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg=="></img>
  </a>
  <a href="https://github.com/felipemjesuss/proffy-api/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/felipemjesuss/proffy-api?color=774DD6">
  </a> 
  <img alt="License" src="https://img.shields.io/badge/license-MIT-8257E5">
  <a href="https://github.com/felipemjesuss/proffy-api/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/felipemjesuss/proffy-api?color=8257E5&logo=github">
  </a>
</p>

> :rocket: Projeto feito para conectar professores e estudantes, feito na Next Level Week #2 @Rocketseat

<div align="center">
  <p>
  <img src="./.github/nlw2.svg" alt="Next Level Week #2" width="100"/>
  </p>
  <sub>The NLW #2 project. Built with ❤︎ by
    <a href="https://github.com/felipemjsuess">Felipe Martins</a> and
    <a href="https://github.com/felipemjsuess/proffy-api/graphs/contributors">
      contributors
    </a>
  </sub>
</div>

# :pushpin: Tabela de Conteúdo

* [Tecnologias](#computer-tecnologias)
* [Funcionalidades](#rocket-funcionalidades)
* [Como rodar](#construction_worker-como-rodar)
* [Encontrou um bug? Ou está faltando uma feature?](#bug-problemas)
* [Contribuindo](#tada-contribuindo)
* [Licencia](#closed_book-licencia)

# 📥 Versões disponiveis do projeto:

- Proffy Web - [https://github.com/felipemjesuss/proffy-web](https://github.com/felipemjesuss/proffy-web)
- Proffy App - [https://github.com/felipemjesuss/proffy-app](https://github.com/felipemjesuss/proffy-app)
- Proffy Api - [https://github.com/felipemjesuss/proffy-api](https://github.com/felipemjesuss/proffy-api)

# :computer: Tecnologias
Esse projeto foi feito utilizando as seguintes tecnologias:
<ul>
  <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
  <li><a href="https://expressjs.com/en/api.html#express">Express</a></li>
</ul>

# :rocket: Funcionalidades

* ```GET /classes``` Retorna lista de aulas disponíveis
* ```GET /classes?week_day=&subject=&time=``` Filtros disponíveis para buscar aulas
* ```POST /classes``` Cadastro de novas aulas, enviar os seguinte objeto 
```json
{
    "name": "Nome do professor",
    "avatar": "Link do avatar do professor",
    "whatsapp": "Número de celular utilizado no WhatsApp",
    "bio": "Pequena descrição sobre a aula",
    "subject": "Nome da disciplina",
    "cost": "Valor hora/aula",
    "schedule": [
        {
            "week_day": "Dia da semana, entre 0 e 6",
            "from": "Hora inicial da disponibilidade no dia",
            "to": "Hora final da disponibilidade no dia"
        }
    ],
}
```
* ```GET /connections``` Total de conexões realizadas com o professor
* ```POST /connections``` Criar nova conexão com o professor
```json
{
    "user_id": "Identificador do professor"
}
```

# :construction_worker: Como rodar
```bash
# Clone o repositorio
$ git clone https://github.com/felipemjesuss/proffy-api.git

# Instale as depedencias
$ yarn

# Rode a aplicação
$ yarn start
```
Acesse a API: http://localhost:3333/

# :bug: Problemas

Fique a vontade **para criar uma nova issue** com o respectivo titulo e descrição na página de issues do [Proffy API](https://github.com/felipemjesuss/proffy-api/issues) Repositorio. Se você já encontrou a solução para o problema, **Eu amaria fazer o review do seu pull request**!

# :tada: Contribuindo

Confira a página de [contribuição](https://github.com/felipemjesuss/proffy-api/blob/master/CONTRIBUTING.md) para ver como começar uma discução e começar a contribuir.

# :closed_book: Licencia

Lançado em 2020 :closed_book: Licencia

Feito com amor por [Felipe Martins](https://github.com/felipemjesuss) 🚀.
Esse projeto esta sobre [MIT license](https://github.com/felipemjesuss/proffy-api/master/LICENSE).


Dê uma ⭐️ se esse projeto te ajudou!

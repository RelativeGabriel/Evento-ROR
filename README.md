## Evento Ruby on Rails I
> Primeiro evento de Ruby on Rails

#

Dependências básicas para rodar o código dentro desse repositório

* Rails 6.0.4.1
* Ruby > 2.5
* Rubygems > 3.2.23
* Bundler > 2.2.23

Instalação do ambiente em máquinas Linux
* [rvm](http://rvm.io/rvm/install)

#

## <p style="background-color: red; color: white; padding: 5px 10px;">Ruby on Rails</p>

Ruby on Rails é um framework baseado na linguagem Ruby que nos possibilita criar e gerenciar aplicações web baseadas no padrão de projeto MVC. O framework nos dá liberdade para trabalhar em conjunto com diversas estruturas pré-definidas e possibilita a entrega de projetos complexos com agilidade, organização e confiabilidade.

#

## <p style="background-color: white; color: black; padding: 5px 10px;">Iniciando um projeto novo</p>

Para iniciar um projeto em Ruby on Rails é necessário utilizar o comando **rails new nome-do-projeto**. Para obter um detalhamento mais aprofundado sobre o comando, basta olhar o seu manual da seguinte forma:

```bash
rails new -h
```

Aqui estão algumas sugestões de opções que podem facilitar sua vida na hora de criar um novo projeto:

* **-d** - Opção usada para você especificar o tipo de database que irá utilizar, podendo, por exemplo, ser mysql, postgresql etc. Por padrão, caso você não utilize a opção, a database será sqlite.

* **--skip-webpack-install** - Para evitar a instalação do webpack que pode causar uma pequena demora na hora da criação do seu projeto.

<br>

Em nosso projeto base foi utilizado o comando a seguir para gerar todo o ambiente de desenvolvimento.

```
rails new evento-ror
```

<br>

Com o projeto criado, já podemos iniciá-lo para fazermos os testes e verificar se tudo está realmente ok em nosso ambiente. Para isso, rode o servidor através do comando

```
rails s
```

#

## <p style="background-color: white; color: black; padding: 5px 10px;">Conceitos teóricas para a aplicação futura</p>

### <u>MVC - Padrão MODEL, VIEW e CONTROLLER</u>
O padrão de projeto MVC é a base da programação em Ruby. Ele consiste na divisão, em camadas, de nossa aplicação, sendo estas camadas as seguintes:

* M - Model: o model é o nosso objeto, sendo este relacionado com o banco de dados.

* V - View: a view é a visualização da página para o usuário, servindo para este introduzir ou receber os dados que desejamos. Vale ressaltar que a view não necessariamente precisa ser HTML, podendo esta ser, por exemplo, um PDF, uma imagem, um XML, um JSON etc.

* C - Controller: o controller é a camada intermediária de nossa aplicação, servindo para fazer a comunicação entre o usuário com o model. O controller tem o papel de receber (através das rotas de suas actions) ou de enviar (através de seus renders) os dados no projeto. O controller trata entratadas e repassa o resultado para o usuário. Vale ressaltar que um controller não armazena dados, fazendo apenas uma ponte para abstrair os tratamentos de dados das views.

<br>

### <u>ORM - Object-Relational Mapping</u>
O mapeamento objeto-relacional é um facilitador para a programação utilizando bancos de dados, fazendo a comunicação dos nossos modelos criados em Ruby com o nosso banco de dados, fazendo uma "tradução" para que a comunicação ocorra de forma limpa e precisa.

<br>

### <u>Camel case e snake case</u>
Camel case e snake case são formas de escrever palavras simples ou compostas, sendo essas formas as seguintes:

* **Camel case**: primeira letra maiúscula e demais palavras também. Por exemplo: traz nota = TrazNota; pula corda = PulaCorda.

* **Snake case**: primeira letra minúscula e demais palavras separadas por underlines. Por exemplo: traz nota = traz_nota; pula corda = pula_corda.

Essas formas de escrever palavras serão utilizadas na criação de métodos em nosso projeto. Será falado, quando necessário, quando se deve optar por um ou outro.

#

## <p style="background-color: white; color: black; padding: 5px 10px;">Codando nossa aplicação</p>

**O CONTEÚDO SERÁ DISPONIBILIZADO APÓS O DIA 18/12**

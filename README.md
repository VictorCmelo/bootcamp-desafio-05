
#  :heavy_check_mark: Desafio 05 - Database upload

Nesse desafio, continuei o desenvolvendo a aplicação de gestão de transações do [desafio 04](https://github.com/VictorCmelo/bootcamp-desafio-04-nodejs), exercitando o que aprendi até agora sobre Node.js junto ao TypeScript, mas dessa vez incluindo o uso de banco de dados com o TypeORM, Docker  e envio de arquivos com o Multer!

##  :whale:  DOCKER  

 Docker é utilizado por ter a habilidade de criar e isolar ambientes necessários para as aplicações. Neste desafio o docker "sobe" nosso container de  banco de dados Postgres.

><details>
> <summary>Imagem</summary>
>  
> - São ferramentas que podem ser colocadas dentro do container
></details>
>
><details>
> <summary>Container</summary>
> 
>- É a instancia de uma imagem
></details>
>
><details>
>  <summary>Docker file</summary>
>  
> - Receita de uma imagem - como funciona
></details>

##  :file_folder:  TypeORM
O TypeORM é um módulo avançado de gerenciamento de relações de objeto que é executado no Node.js. Como o nome indica, o TypeORM deve ser usado com o TypeScript.  usar o TypeORM para configurar objetos Entity para armazenar dados em um banco de dados, como usar uma instância CustomRepository para manipular uma tabela de banco de dados e usar Relações entre instâncias de Entidade para simular junções de banco de dados. 

### Alguns comandos úteis:
 - migrations : migrações que serão carregadas, exeplo (criação de uma table) 

```
yarn typeorm migration:create -n NomedaMigration

yarn typeorm migration:run

yarn typeorm migration:revert 

```

## :paperclip:  Multer 

Multer é um middlware capaz de interceptar as rotas antes da execução e realizar  o upoad de  arquivos atralado ao Express e ao NodeJs.

Um guia completo por ser acessado [aqui](http://cangaceirojavascript.com.br/express-realizando-upload-multer/)





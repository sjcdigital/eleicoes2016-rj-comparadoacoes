# Sobre o projeto

O TSE(Tribunal Superior Eleitoral) libera dados sobre todas as candidaturas no Brasil, sendo que uma em particular
é muito interessante, a de doações, onde podemos ver quem são aqueles que financiam os políticos.

Partindo desse ponto, esse projeto é para fornecer um comparador de doações de campanha entre candidatos a prefeito
do Rio de Janeiro, facilitando visualizar diferenças na forma como cada um está bancando sua campanha.

# Detalhes técnicos

## Como rodar o crawler
Estando na pasta "/data/crawler", execute "php generate.php" e o arquivo "/data/doacoes_geral.json" será atualizado.

## Rodando a Aplicação:

Instale as dependências com o Node:

```sh
$ npm i
```

Para rodar a aplicação:

```sh
$ npm start
```

Para fazer deploy:
```sh
$ npm deploy
```

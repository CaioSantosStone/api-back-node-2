#### Inicio ####

## Instalação
-NODE versão 12 >

-npm install

-Recomendado possuir um executador de request exemplo "Postman"

## Execução
-npm start
-npm test

## Descrição Geral e Ajuda

-Esse é um projeto basico em nodejs utilizando express, serve de base para o inicio do live code, caso queira utilizar um outro projeto, voce está livre para seguir esse caminho, mas terá que justificar sua escolha e saiba que isso ira te custar um certo tempo então seja acertivo caso queira realizar essa mudança.

-O projeto lida com teste com chai e mocha para exemplificar suas funcionalidades, nada o impede de trocar o padrão ou framework de teste, mas saiba que isso ira te custar um certo tempo então seja acertivo caso queira realizar essa mudança.

-A internet e projetos antigos são seus amigos, não queremos e nem esperamos que voce saiba tudo de cabeça, mas que consiga resolver problemas que podem surgir no seu dia a dia, então pode consultar a vontade, somente deixe a tela sendo compartilhada, queremos ver sua evolução.

Então bora para o desafio abaixo:

#### Controle saque de valores disponíveis de transação ####

## Será avaliado
- Simplicidade.
- Consistência da visão das regras de negócio.
- Manutenção.
- Testabilidade.
- Entendimento do codigo.


É necessário que o gerenciamento de usuarios seja executado corretamente.
Para iniciar este gerenciamento o seguinte objetivo deve ser alcançados ao realizar a implementação de sua regra de negócio.

##Objetivo

1- Executar uma filtragem e retornar os usuários que foram enviados por uma base de clientes. Para ser um usuário válido, é necessário possuir um nome, data de nascimento menor que 1996(Mais Velhos), um e-mail válido e estar desativado, pois usuários ativos não são úteis para o usuário que está querendo essas informações e colhendo feedbacks de usuários que deixaram a plataforma. Para essa filtragem, crie um endpoint do tipo GET e retorne uma lista contendo os usuários e a soma dos usuários retornados.

Exemplo de resposta:
```
{
    list_user: [],
    user_total: number
}
```

##Base de dados explicada>Caminho>App/Database/Database.js
```
{
    name: "",//nome do usuario
    birth_data: "",//data de nascimento
    email: "",//email do usuario
    created_at: ""//data de criacao
    is_active: true, //saber se o usuario esta ativo ou nao
}
```

##Instrução final
-Queremos entender como sua mente funciona, então tente se sentir o mais avontade possivel, caso queira buscar uma agua, cafe ou ir ao banheiro, sem problema algum, o processo aqui é mais importante que o resultado final.

-Existem exemplos que podem ser visto na pasta ExampleRoute quanto para requisição post quanto get. -Rota: http://localhost:3000/lorem-ipsum
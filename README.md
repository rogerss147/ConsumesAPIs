# Consumes APIs
The idea of ​​this repository will s consumed by a third party.

## Ideia do projeto
A ideia inicial desse projeto é:
 - Criar uma API de cadastro de pessoas
 - Cadastrar essas pessoas usando um BD NOSQL
   - Cassandra;
   - Mongo;
 - Dados a serem cadastrados:
   - Nome
   - Sobre nome
   - Documento
   - Telefone
 - Criar uma pagina de envio de SMS simples:
   - A pagina deverá ter o nome do destinatário (validar se o nome do destinatario existe no banco caso exista deve-se utilizar os dados provenientes do banco se não deve-se colocar um contato novo e toda vez que for adicionado um contato novo o mesmo deve ser cadastrado no banco de dados.)
   - Deve haver uma caixa de mensagem para adicionar a mensagem que seguira ao destinatario.
   - O envio da mensagem será feito utilizando um serviço de api aberta.
   [1] https://www.twilio.com/docs/sms/send-messages
   Todo o entendimento da documentação deverá ser feito.

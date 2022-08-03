***

## 1. Introdução

História de usuário é um tipo de narrativa simples que ilustra um requisito do usuário da perspectiva de uma persona ou cliente; fazem parte de uma estrutura ágil e de explicação informal. Um dos objetivos das histórias é mostrar como uma tarefa entregará determinado valor ao usuário.

As histórias de usuário possuem um ator ("Eu, como **usuário**..."), uma função ("...gostaria de **criar uma conta**...") e uma razão ("...**para ter acesso a todas as funções do aplicativo**"). As histórias de usuário também possuem critérios de aceitação, que definem as condições para que aquela história seja considerada entregue.

## 2. Histórias de usuários

Na tabela a seguir é possível ver as histórias de usuário, juntamente com seus critérios de aceitação e a rastreabilidade, que faz referência ao requisito ao qual foi baseada essa história.

Legenda:

- US = identificador da História de usuário (_User Story_)

<center>

| ID | História de usuário |Critérios de aceitação| Rastreabilidade |
|----|----|----|----|
|US1|Eu, como usuário, gostaria de agendar atendimento presencial para realizar um serviço | - Deve ser possível inserir dados do usuário(nome, CPF, E-mail e telefone)<br>- Deve ser possível selecionar o serviço<br>- Deve ser possível escolher unidade de agendamento<br>- Deve ser possível escolher data de agendamento<br>- Deve ser possível escolher hora de agendamento<br>- Deve apresentar o endereço da unidade ao confimar cadastro de agendamento  |RF6, RF13, RF36, RF37, RF38, RF39, RF40|
|US2|Eu, como usuário, gostaria de consultar os débitos do veículo para poder gerar o boleto e pagar as multas|deve ser possível inserir placa e renavam do veículo |RF4, RF9|
|US3|Eu, como usuário, gostaria de consultar débitos, restrições, financiamento e quilometragem do veículo para poder estar ciente dessas informações| deve ser possível inserir placa e renavam do veículo |RF11|
|US4|Eu, como usuário, gostaria de realizar a tranferência do meu veículo pelo aplicativo para não precisar ir até uma unidade presencial| deve ser possível selecionar entre proprietário ou comprador      |RF16|
|US5|Eu, como usuário, gostaria de emitir o CRLV para poder ter acesso de forma digital| deve ser possível selecionar veículo   |RF18|
|US6|Eu, como usuário, gostaria de alterar o endereço de veículo pelo aplicativo para não precisar ir até uma unidade presencial| deve ser possível alterar dados de endereço do veículo    |RF19|
|US7|Eu, como usuário, gostaria de emitir o ATPV para poder ter acesso de forma digital|deve ser possível selecionar veículo|RF20|
|US8|Eu, como usuário, gostaria de marcar vistoria para o veículo |- deve ser possível selecionar tipo de vistoria(transfeência de veículo, inclusão gravame e alteração de caracteristica)<br>- deve ser possível inserir placa e renavam do veículo|RF21|
|US9|Eu, como usuário, gostaria de me registrar no aplicativo |- deve ser possível verficar o CPF ou CNPJ do usuário<br>- deve ser possível inserir um e-mail para cadastro<br>- deve ser possível informar uma senha<br>- deve ser possível recuperar a senha<br>-deve ser possível alterar o e-mail|RF1, RF46|
|US10|Eu, como usuário, gostaria de realizar meu login no aplicativo |- deve ser possível inserir o CPF ou CNPJ do usuário<br>- deve ser possível informar a senha|RF2|
|US11|Eu, como usuário, gostaria de visualizar minha CNH eletrônica |- deve ser possível selecionar a opção de visualização<br>- deve ser possível visualizara CNH pelo aplicativo |RF3, RF10, RF22|
|US12|Eu, como usuário, gostaria de visualizar a quantidade de pontos na minha carteira |- deve ser possível visualizar a quantidade total de infrações<br>- deve ser possível visualizar a quantidade total de pontos<br>- deve ser possível transferir a pontuação |RF5, RF12, RF32, RF34, RF33, RF47|
|US13| Eu, como usuário, gostaria de solicitar minha 2a via de CNH |- deve ser possível preencher os dados para o envio da nova CNH<br>- deve ser possível gerar um boleto para o pagamento |RF8, RF28|
|US14|Eu, como usuário, gostaria de visualizar minhas multas |- deve ser possível visualizar a quantidade total de multas<br>- deve ser possível saber o valor da multa<br>- deve ser possível gerar um boleto para o pagamento da multa |RF9, RF14, RF35|
|US15|Eu, como usuário, gostaria de sabe sobre o bloqueio da minha CNH |- deve ser possível saber se a CNH está bloqueada<br>- deve ser possível saber o motivo do bloqueio |RF23|
|US16|Eu, como usuário, gostaria de saber informações sobre ocorrências |- deve ser possível visualizar se há uma ocorrência para o usuário logado<br>- deve ser possível realizar o Boletim de Ocorrência pelo aplicativo |RF24|
|US17|Eu, como usuário, gostaria consultar o Nada Consta |- deve ser possível visualizar o documento<br>- deve ser possível emitir o documento|RF25|
|US18|Eu, como usuário, gostaria de alterar meu endereço |- deve ser possível visualizar o endereço que já está cadastrado<br>- deve ser possível alterar cada um dos campos que compõem o endereço|RF31|
|US19|Eu, como usuário, gostaria de alterar meus dados cadastrais |- deve ser possível alterar o e-mail cadastrado<br>- deve ser possível alterar a senha cadastrada<br>- deve ser possível recuperar a senha do usuário<br>-deve ser possível deletar a conta|RF42, RF43, RF48|


<h6 align = "center">Tabela 1: histórias de usuário</h6>
</center>

## 3. Referências

> User story. Software and Systems Engineering Vocabulary. Disponível em: <https://pascal.computer.org/sev_display/index.action>. Acesso em: 30/07/2022

> User story. awari. Disponível em: <https://awari.com.br/user-story/>. Acesso em: 30/07/2022

***
## Histórico de Versão

|  Versão   | Data       | Descrição           | Autor  | Revisor|
|:---------:|------------|---------------------|--------|--------|
| 0.1 | 30/07/2022 | Criação do documento, adição do tópico de Introdução e US's de 1 a 8 | Alex | Matheus  |
| 0.2 | 01/08/2022 | Adição de US's de 9 a 12 | Matheus | Alex |
| 0.3 | 02/08/2022 | Adição de US's de 13 a 19 | Matheus | Alex |

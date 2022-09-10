# Backlog
## 1. Introdução
O *Product Backlog* é uma lista de itens a serem implementados dentro do escopo de desenvolvimento de software, em que os 
itens são priorizados de acordo com o valor que cada funcionalidade agrega para o cliente. O backlog é atualizado e sofre 
alterações durante o processo de desenvolvimento, em conformidade com o andamento do projeto. Dentro de uma abordagem Ágil, 
os itens dos backlog são desenvolvidos ao longo de Sprints, que englobam determinada quantidade de itens do Backlog. Já
em um contexto tradicional, como Kanban, o desenvolvimento acontece de forma linear, com o foco na execução completa da tarefa
sem quebrar o fluxo de trabalho.

## 2. Épicos
Trata-se de uma modelagem que permite ao cliente definir o que é importante para o projeto, bem como o que é
desnecessário. Uma vez definida a importância dos módulos de um projeto, é possível separar e agrupar os itens do backlog,
facilitando a organização e a [priorização](../../elicitação/priorização/moscow.md). Em sua definição formal, pode-se afirmar que épicos são definidos como: “iniciativas
de desenvolvimento que tem como objetivo entregar valor à um tema de investimento” (LEFFINGWELL, 2010).

## 3. Histórias de Usuários
Uma história de usuário é uma representação descomplicada e informal de uma necessidade de um usuário em potencial e
tem como objetivo expressar sucintamente, as dores e necessidades desse usuário, para que a equipe, posteriormente,
proponha critérios mínimos para aceitação e defina a viabilidade da história. Além, de apresentar o valor de negócio
agregado ao produto de uma forma simples e leve.

### 3.1. EP01 - Conta
A tabela abaixo ilustra a lógica de contrução do épico **Conta** (mais detalhes [aqui](epConta.md)):

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US01 | RF1 | Criar conta | Ter acesso ao sistema | Must |
| US02 | RF2 | Realizar login | Acessar o conteúdo da plataforma | Must |
| US03 | RF42| Alterar email | Utilizar um novo email no sistema | Must |
| US04 | RF43 | Alterar senha | Utilizar uma nova senha para login | Must |
| US05 | RF45 | Cadastrar biometria | Acessar plataforma por biometria | Must |
| US06 | RF46| Cadastrar CPF/CNPJ | Usar como documento de usuário | Must |
<h6 align = "center"> Tabela 1: Épico de Contas</h6>

### 3.2. EP02 - Habilitação
A tabela abaixo ilustra a lógica de contrução do épico **Habilitação** (mais detalhes [aqui](epHabilitacao.md)):

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US07 | RF3 | Visualizar CNH eletrônica | Ter acesso aos dados da CNH | Must |
| US08 | RF8 | Solicitar segunda via da CNH | Receber uma nova CNH | Must |
| US09 | RF28| Solicitar CNH definitiva | Receber a sua CNH definitiva | Must |
| US10 | RF31 | Modificar endereço da CNH  | Trocar de endereço | Should |
| US11 | RF20 | Emitir CNH digital| Ter acesso à CNH digital | Must |
<h6 align = "center"> Tabela 2: Épico de Habilitação</h6> 

### 3.3. EP03 - Veículos
A tabela abaixo ilustra a lógica de contrução do épico **Veículos** (mais detalhes [aqui](epVeiculo.md)):

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US12 | RF11 | Consultar veículo | Ter acesso às informações do veículo | Must |
| US13 | RF17 | Consultar histórico do veículo | Ter acesso ao histórico do veículo | Should |
| US15 | RF29 | Solicitar estacionamento para idosos  | Ter authorização para estacionar em vagas reservadas | Must |
| US16 | RF30 | Solicitar estacionamento para PCDs  | Ter authorização para estacionar em vagas reservadas | Must |
<h6 align = "center"> Tabela 3: Épico de Veículos</h6> 

### 3.4. EP04 - Infrações
A tabela abaixo ilustra a lógica de contrução do épico **Infrações** (mais detalhes [aqui](epInfracao.md)):

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US17 | RF12 | Consultar infrações | Ter acesso às informações sobre infrações | Must |
| US18 | RF14 | Consultar multas | Ter acesso as multas | Should |
| US19 | RF24 | Consultar pontuação associada ao condutor  | Ter acesso à pontuação | Should |
| US20 | RF33 | Transferir pontos de infração | Fazer a transferência dos pontos de infração| Should |
| US21 | RF34 | Transferir titularidade de multa | Fazer a transferência da titularidade da multa| Should |
| US22 | RF35 | Realizar pagamento de multa | Quitar uma multa | Should |
<h6 align = "center"> Tabela 4: Épico de Infrações</h6> 

### 3.5. EP05 - Agendamentos
A tabela abaixo ilustra a lógica de contrução do épico **Agendamentos** (mais detalhes [aqui](epAgendamento.md)):

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US23 | RF6 | Agendar atendimento presencial | marcar uma data sem precisar ir pessoalmente solicitar o mesmo | Must |
| US24 | RF21 | Agendar vistorias veiculares online | marcar uma data sem precisar ir pessoalmente solicitar o mesmo | Could |
| US25 | RF38 | Escolher uma unidade de agendamento | escolher onde será o atendimento | Could |
| US26 | RF39 | Escolher a hora de agendamento| ter liberdade diante minha rotina de horários | Could |
<h6 align = "center"> Tabela 5: Épico de Agendamentos</h6> 

## 4. Referências Bibliográficas
> LEFFINGWELL, D. Agile software requirements: lean requirements practices for teams,
programs, and the enterprise. [S.l.]: Addison-Wesley Professional, 2010.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 01/08/2022 | Criação do documento | Paulo Gotinjo e Thiago Gomes | Arthur|
| 0.2 | 02/08/2022 | Criação dos épicos e reformatação do texto | Thiago Gomes e Paulo Gotinjo | Arthur|




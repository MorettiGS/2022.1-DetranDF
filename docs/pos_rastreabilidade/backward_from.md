## 1. introdução

## 2. Metodologia

## 3. Rastreabilidade requisitos funcionais

| Número    | Requisito                                                                  | Origem    |Elos|
| :-: |-|:-:|:-:|
| RF01 |O usuário deve ser capaz de se registrar no aplicativo                            |Introspecção|[**EF01**](#ef01)|
| RF02 |O usuário deve ser capaz de fazer o login na sua conta                            |Introspecção|[**EF02**](#ef02)|
| RF03 |O usuário deve ser capaz de visualizar sua CNH eletrônica                         |Introspecção|[**EF03**](#ef03)|
| RF04 |O usuário deve ser capaz de visualizar suas multas                                |Introspecção|[**EF04**](#ef04)|
| RF05 |O usuário deve ser capaz de consultar os pontos da carteira                       |Introspecção|[**EF05**](#ef05)|
| RF06 |O usuário deve ser capaz de fazer um agendamento de atendimento presencial        |Introspecção|[**EF06**](#ef06)|
| RF07 |O usuário deve ser capaz de encontrar os números de contato do Detran             |Introspecção|[**EF07**](#ef07)|
| RF08 |O usuário deve ser capaz de solicitar 2ª via da CNH                               |Introspecção|[**EF08**](#ef08)|
| RF09 |O usuário deve ser capaz de gerar boletos para pagar suas multas                  |Introspecção|[**EF09**](#ef09)|
| RF10 |Deverá ser possível acessar a habilitação	                                     |Questionário|[**EF10**](#ef10)|
| RF11 |Deverá ser possível consultar o veículo                                          |Questionário|[**EF11**](#ef11)|
| RF12 |Deverá ser possível consultar infrações                                          |Questionário|[**EF12**](#ef12)|
| RF13 |Deverá ser possível agendar atendimentos                                         |Questionário|[**EF13**](#ef13)|
| RF14 |Deve ser possível consultar informações sobre multas                               |Brainstorm|[**EF14**](#ef14)|
| RF15 |Deve ser possível consultar informações sobre documentos                           |Brainstorm|[**EF15**](#ef15)|
| RF16 |Deve ser possível realizar transferências de veículos de forma eletrônica          |Brainstorm|[**EF16**](#ef16)|
| RF17 |Deve ser possível consultar informações históricas sobre o veículo                 |Brainstorm||
| RF18 |Deve ser possível emitir eletrônicamente o CRLV                                    |Brainstorm||
| RF19 |Deve ser possível alterar o endereço do proprietário do veículo                    |Brainstorm||
| RF20 |Deve ser possível emitir o ATPV                                                    |Brainstorm||
| RF21 |Deve ser possível agendar vistorias veiculares                                     |Brainstorm||
| RF22 |Deve ser possível emitir CNH eletrônica                                            |Brainstorm||
| RF23 |Deve ser possível consultar informações sobre bloqueios                            |Brainstorm||
| RF24 |Deve ser possível consultar informações sobre ocorrências                          |Brainstorm||
| RF25 |Deve ser possível emitir documento de nada consta                                  |Brainstorm||
| RF26 |Deve ser possível consultar informações sobre processo de obtenção da habilitação  |Brainstorm||
| RF27 |Deve ser possível solicitar CNH definitiva                                         |Brainstorm||
| RF28 |Deve ser possível solicitar 2ª via de CNH                                          |Brainstorm||
| RF29 |Deve ser possível solicitar autorização de estacionamento para idosos              |Brainstorm||
| RF30 |Deve ser possível solicitar autorização de estacionamento para PCDs                |Brainstorm||
| RF31 |Deve ser possível modificar endereço do proprietário da CNH                        |Brainstorm||
| RF32 |Deve ser possível consultar infrações                                              |Brainstorm||
| RF33 |Deve ser possível transferir pontos de infrações                                   |Brainstorm||
| RF34 |Deve ser possível transferir titularidade de multa                                 |Brainstorm||
| RF35 |Deve ser possível realizar pagamento de multa                                      |Brainstorm||
| RF36 |Deve ser possível agendar serviços                                                 |Brainstorm||
| RF37 |Deve ser possível escolher data de agendamento                                     |Brainstorm||
| RF38 |Deve ser possível escolher unidade de agendamento                                  |Brainstorm||
| RF39 |Deve ser possível escolher hora de agendamento                                     |Brainstorm||
| RF40 |Deve ser possível consulta endereço de unidades                                    |Brainstorm||
| RF41 |Deve ser possível realizar contato com ouvidoria                                   |Brainstorm||
| RF42 |Deve ser possível alterar email                                                    |Brainstorm||
| RF43 |Deve ser possível alterar senha                                                    |Brainstorm||
| RF44 |Deve ser possível reenviar e-mail de validação                                     |Brainstorm||
| RF45 |Deve ser possível cadastrar biometria                                              |Brainstorm||
| RF46 |Deve ser possível cadastrar Cpf/Cnpj                                               |Brainstorm||
| RF47 |Deve ser possível consultar pontuação de infrações associadas ao condutor          |Brainstorm||
| RF48 |Deve ser possível cadastrar uma senha                                              |Brainstorm||


<h6 align = "center">Tabela 1: Rastreabilidade de requisitos funcionais</h6>

## 4. Rastreabilidade de requisitos não funcionais 

| Número     | Requisito   | Origem    |Elos|
|:------------:|-----------------|------------|-----|
|RNF1|O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS|Introspecção|[**ENF01**](#enf01)|
|RNF2|O aplicativo deve ter uma latência máxima de 1000ms por requisição             |Introspecção||
|RNF3|O aplicativo deve estar disponível 24h                                         |Introspecção, Questionário||

<h6 align = "center">Tabela 2: Rastreabilidade de requisitos não funcionais</h6>

## **5. Elos funcionais**

### EF01

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [US01](../modelagem/backlog/epConta.md) representa RF01<br>
Representação: [Caso 1](../modelagem/casos.md) representa [C01](../modelagem/cenarios.md)<br>
Representação: [C01](../modelagem/cenarios.md) representa [Léxico: Registrar](../modelagem/lexico.md)
### EF02

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [US02](../modelagem/backlog/epConta.md) representa RF02<br>
Representação: [Caso 2](../modelagem/casos.md) representa [C02](../modelagem/cenarios.md)<br>
Representação: [C02](../modelagem/cenarios.md) representa [Léxico: Login](../modelagem/lexico.md)

### EF03

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Caso 3](../modelagem/casos.md) representa RF03<br>
Representação: [US07](../modelagem/backlog/epHabilitacao.md) representa [Caso 3](../modelagem/casos.md) 

### EF04

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: Visualizar multa](../modelagem/lexico.md) representa RF04<br>
Representação: [US18](../modelagem/backlog/epInfracao.md) representa [Caso 4](../modelagem/casos.md)

### EF05

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: Consultar Pontos](../modelagem/lexico.md) representa RF05 <br>
Representação: [C05](../modelagem/cenarios.md) representa [caso 3](../modelagem/casos.md)

### EF06

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: Agendamento](../modelagem/lexico.md) representa [C07](../modelagem/cenarios.md)<br>
Representação: [Caso 6](../modelagem/casos.md)  representa [US23](../modelagem/backlog/epAgendamento.md)

### EF07

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: Contato](../modelagem/lexico.md) representa RF07<br>
Representação: [Prototipo](../analise/validacao/prototipacao.md) representa [Léxico: Contato](../modelagem/lexico.md)

### EF08

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [C05](../modelagem/cenarios.md) representa [caso 3](../modelagem/casos.md)<br>
Representação: [caso 3](../modelagem/casos.md) representa [US08](../modelagem/backlog/epHabilitacao.md)

### EF09

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Prototipo](../analise/validacao/prototipacao.md) representa RF09
### EF10

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: CNH](../modelagem/lexico.md) representa [C05](../modelagem/cenarios.md)<br>
Representação: [caso 3](../modelagem/casos.md) representa [US07](../modelagem/backlog/epHabilitacao.md)

### EF11

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [Léxico: Consultar o Veículo](../modelagem/lexico.md) representa [C04](../modelagem/cenarios.md)<br>
Representação: [caso 4](../modelagem/casos.md) representa [US12](../modelagem/backlog/epVeiculo.md)

### EF12

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [caso 5](../modelagem/casos.md) representa [C06](../modelagem/cenarios.md)<br>
Representação:  [US17](../modelagem/backlog/epInfracao.md) representa [caso 5](../modelagem/casos.md) 

### EF13

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação:[Léxico: Agendamento](../modelagem/lexico.md) representa [C07](../modelagem/cenarios.md)<br>
Representação:[Caso 6](../modelagem/casos.md) representa [US23](../modelagem/backlog/epHabilitacao.md)

### EF14

**Categoria:** Desenvolvimento

**Elos:** <br>
Agregação: [BT01](../elicita%C3%A7%C3%A3o/brainstorm.md) agrega [INT04](../elicita%C3%A7%C3%A3o/introspeccao.md)

### EF15

**Categoria:** --

**Elos:** --

### EF16

**Categoria:** Desenvolvimento

**Elos:** <br>
Representação: [C04](../modelagem/cenarios.md) representa [Caso 4](../modelagem/casos.md)

## **6. Elos não funcionais**

### ENF01

**Categoria:** Desenvolvimento

**Elos:** <br>
Agregação: [RNF1](../modelagem/especificacao.md) agrega [Suportabilidade](../modelagem/nfr.md)

## Referências
> Slides da aula 26 de requisitos de software UnB-FGA, Milene Serrano e Maurício Serrano
## Histórico de Versão
| Versão |     Data     |              Descrição               |      Autor      | Revisor |
|:------:|:------------:|:------------------------------------:|:---------------:|:------:|
|  0.1   |  19/07/2022  |         Criação do documento         |  | |

# Matriz Geral

## 1. Introdução

Este documento tem por objetivo reunir todos os requisitos levantados no [backward from](backward_from.md) e [forward from](forward_from.md) através de uma matriz geral de rastreabilidade

## 2. Matriz Geral

| Número    | Requisito                                                                   | Origem     | História de usuário | Léxico | Cenário | Elos |
| :-: |-|:-:|:-:|:-:|:-:|:-:|
| RF01 |O usuário deve ser capaz de se registrar no aplicativo                            |Introspecção| US01 | Registrar | C01 | [EF01](backward_from.md#ef01) |
| RF02 |O usuário deve ser capaz de fazer o login na sua conta                            |Introspecção| US02 | Login | C02 | [EF02](backward_from.md#ef02) |
| RF03 |O usuário deve ser capaz de visualizar sua CNH eletrônica                         |Introspecção| US05 | | C05 |[EF03](backward_from.md#ef03) |
| RF04 |O usuário deve ser capaz de visualizar suas multas                                |Introspecção| US10 | Visualizar Multa | C06 |[EF04](backward_from.md#ef04) |
| RF05 |O usuário deve ser capaz de consultar os pontos da carteira                       |Introspecção| US18 | Consultar pontos | |[EF05](backward_from.md#ef05) |
| RF06 |O usuário deve ser capaz de fazer um agendamento de atendimento presencial        |Introspecção| US17 | Agendamento | |[EF06](backward_from.md#ef06) |
| RF07 |O usuário deve ser capaz de encontrar os números de contato do Detran             |Introspecção|      | Contato | |[EF07](backward_from.md#ef07) |
| RF08 |O usuário deve ser capaz de solicitar 2ª via da CNH                               |Introspecção| US06 | | C05 | [EF08](backward_from.md#ef08) |
| RF09 |O usuário deve ser capaz de gerar boletos para pagar suas multas                  |Introspecção| US10 | Gerar Boleto | C06 |[EF09](backward_from.md#ef09) |
| RF10 |Deverá ser possível acessar a habilitação	                                      |Questionário| US05 | | C05 |[EF10](backward_from.md#ef10) |
| RF11 |Deverá ser possível consultar o veículo                                           |Questionário| US11 | Consultar Veículo | |[EF11](backward_from.md#ef11) |
| RF12 |Deverá ser possível consultar infrações                                           |Questionário| US18 | | |[EF12](backward_from.md#ef12) |
| RF13 |Deverá ser possível agendar atendimentos                                          |Questionário| US17 | Agendamento | |[EF13](backward_from.md#ef13) |
| RF14 |Deve ser possível consultar informações sobre multas                               |Brainstorm| US18 | | C06 |[EF14](backward_from.md#ef14) |
| RF15 |Deve ser possível consultar informações sobre documentos                           |Brainstorm| | | |[EF15](backward_from.md#ef15) |
| RF16 |Deve ser possível realizar transferências de veículos de forma eletrônica          |Brainstorm| US12 | ||[EF16](backward_from.md#ef16) |
| RF17 |Deve ser possível consultar informações históricas sobre o veículo                 |Brainstorm| | ||[EF17](backward_from.md#ef17) |
| RF18 |Deve ser possível emitir eletrônicamente o CRLV                                    |Brainstorm| US13 | ||[EF18](backward_from.md#ef18) |
| RF19 |Deve ser possível alterar o endereço do proprietário do veículo                    |Brainstorm| US14 | ||[EF19](backward_from.md#ef19) |
| RF20 |Deve ser possível emitir o ATPV                                                    |Brainstorm| US15 | ||[EF20](backward_from.md#ef20) |
| RF21 |Deve ser possível agendar vistorias veiculares                                     |Brainstorm| US16 | | C04 |[EF21](backward_from.md#ef21) |
| RF22 |Deve ser possível emitir CNH eletrônica                                            |Brainstorm| US05 | | C05 |[EF22](backward_from.md#ef22) |
| RF23 |Deve ser possível consultar informações sobre bloqueios                            |Brainstorm| US07 | ||[EF23](backward_from.md#ef23) |
| RF24 |Deve ser possível consultar informações sobre ocorrências                          |Brainstorm| US08 | ||[EF24](backward_from.md#ef24) |
| RF25 |Deve ser possível emitir documento de nada consta                                  |Brainstorm| US09 | ||[EF25](backward_from.md#ef25) |
| RF26 |Deve ser possível consultar informações sobre processo de obtenção da habilitação  |Brainstorm| | | C05 |[EF26](backward_from.md#ef26) |
| RF27 |Deve ser possível solicitar CNH definitiva                                         |Brainstorm| | | C05 |[EF27](backward_from.md#ef27) |
| RF28 |Deve ser possível solicitar 2ª via de CNH                                          |Brainstorm| US06 | | C05 |[EF28](backward_from.md#ef28) |
| RF29 |Deve ser possível solicitar autorização de estacionamento para idosos              |Brainstorm| | ||[EF29](backward_from.md#ef29) |
| RF30 |Deve ser possível solicitar autorização de estacionamento para PCDs                |Brainstorm| | ||[EF30](backward_from.md#ef30) |
| RF31 |Deve ser possível modificar endereço do proprietário da CNH                        |Brainstorm| US03 | | C05 |[EF31](backward_from.md#ef31) |
| RF32 |Deve ser possível consultar infrações                                              |Brainstorm| US18 | ||[EF32](backward_from.md#ef32) |
| RF33 |Deve ser possível transferir pontos de infrações                                   |Brainstorm| US18 | ||[EF33](backward_from.md#ef33) |
| RF34 |Deve ser possível transferir titularidade de multa                                 |Brainstorm| | | C06 |[EF34](backward_from.md#ef34) |
| RF35 |Deve ser possível realizar pagamento de multa                                      |Brainstorm| US19 | | C06 |[EF35](backward_from.md#ef35) |
| RF36 |Deve ser possível agendar serviços                                                 |Brainstorm| US17 | | C07 |[EF36](backward_from.md#ef36) |
| RF37 |Deve ser possível escolher data de agendamento                                     |Brainstorm| US17 | Agendamento | C07 |[EF37](backward_from.md#ef37) |
| RF38 |Deve ser possível escolher unidade de agendamento                                  |Brainstorm| US17 | Agendamento | C07 |[EF38](backward_from.md#ef38) |
| RF39 |Deve ser possível escolher hora de agendamento                                     |Brainstorm| US17 | Agendamento | C07 |[EF39](backward_from.md#ef39) |
| RF40 |Deve ser possível consulta endereço de unidades                                    |Brainstorm| US17 | ||[EF40](backward_from.md#ef40) |
| RF41 |Deve ser possível realizar contato com ouvidoria                                   |Brainstorm| | Contato ||[EF41](backward_from.md#ef41) |
| RF42 |Deve ser possível alterar email                                                    |Brainstorm| US04 |||[EF42](backward_from.md#ef42) |
| RF43 |Deve ser possível alterar senha                                                    |Brainstorm| US04 |||[EF43](backward_from.md#ef43) |
| RF44 |Deve ser possível reenviar e-mail de validação                                     |Brainstorm| | ||[EF44](backward_from.md#ef44) |
| RF45 |Deve ser possível cadastrar biometria                                              |Brainstorm| | Registrar ||[EF45](backward_from.md#ef45) |
| RF46 |Deve ser possível cadastrar Cpf/Cnpj                                               |Brainstorm| US01 | Registrar ||[EF46](backward_from.md#ef46) |
| RF47 |Deve ser possível consultar pontuação de infrações associadas ao condutor          |Brainstorm| US18 | Registrar | C06 |[EF47](backward_from.md#ef47) |
| RF48 |Deve ser possível cadastrar uma senha                                              |Brainstorm| US04 | Registrar | C01 |[EF48](backward_from.md#ef48) |
| RNF1 |O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS    |Introspecção||||[ENF01](backward_from.md#enf01)|
| RNF2 |O aplicativo deve ter uma latência máxima de 1000ms por requisição                 |Introspecção||||[ENF02](backward_from.md#enf02)|
| RNF3 |O aplicativo deve estar disponível 24h                                             |Introspecção, Questionário||||[ENF03](backward_from.md#enf03)|

## 3. Histórico de Versão

| Versão |     Data     |              Descrição               |      Autor      | Revisor |
|:------:|:------------:|:------------------------------------:|:---------------:|:-------:|
|  0.1   |  09/09/2022  |         Criação do documento         | Arthur          | Alex    |
|  0.2   |  10/09/2022  |         Adição dos elos              | Arthur          | Alex    |
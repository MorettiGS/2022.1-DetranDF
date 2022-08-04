# EP02 - Habilitação
A tabela abaixo ilustra o épico **Habilitação**:

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US07 | RF3 | Visualizar CNH eletrônica | Ter acesso aos dados da CNH | Must |
| US08 | RF8 | Solicitar segunda via da CNH | Receber uma nova CNH | Must |
| US09 | RF28| Solicitar CNH definitiva | Receber a sua CNH definitiva | Must |
| US10 | RF31 | Modificar endereço da CNH  | Trocar de endereço | Should |
| US11 | RF20 | Emitir CNH digital | Ter acesso à CNH | Must |
<h6 align = "center"> Tabela 1: Épico de Habilitação</h6> 

## 1. US07
Eu, como **usuário** gostaria de **visualizar a CNH eletrônica** para poder **ter acesso aos dados da CNH**.

### 1.1. Critérios de avaliação
* Deve haver uma página que redireciona para o documento da CNH eletrônica.
* O documento deve ser digitalizádo.
* Deve ser possível fazer o download do documento em formato **PDF**.

## 2. US08
Eu, como **usuário** gostaria de **solicitar segunda via da CNH** para poder **receber uma nova CNH**.

### 2.1. Critérios de avaliação
* Deve haver uma seção que requisita ao sistema a emissão do documento.
* O usuário deve receber uma posição frente ao status da operação: sucesso ou falha.
* Deve ser possível consultar a data e a hora da solicitação.

## 3. US09
Eu, como **usuário** gostaria de **solicitar CNH definitiva** para poder **receber a CNH definitiva**.

### 3.1. Critérios de avaliação
* Deve haver uma seção que requisita ao sistema a emissão da CNH definitiva.
* O usuário deve ter a CNH com o status **provisório** para solicitar a definitiva.
* O usuário deve receber uma posição frente ao status da operação: sucesso ou falha.
* Deve ser possível consultar a data e a hora da solicitação.

## 4. US09
Eu, como **usuário** gostaria de **modificar o endereço da CNH** para poder **atualizar o endereço cadastrado**.

### 4.1. Critérios de avaliação
* Deve haver uma seção que requisita ao sistema a alteração do endereço.
* O usuário deve receber uma posição frente ao status da operação: sucesso ou falha.
* Deve ser possível consultar a data e a hora da solicitação.

## 5. US11
Eu, como **usuário** gostaria de **emitir CNH digital** para poder **ter acesso digitalmente a CNH**.

### 5.1. Critérios de avaliação
* Deve haver uma seção que requisita ao sistema a emissão do documento.
* O usuário deve ter a CNH com o status **físico** para solicitar a definitiva.
* O usuário deve receber uma posição frente ao status da operação: concluído ou falha.
* Deve ser possível consultar a data e a hora da solicitação.


## 6. Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 02/08/2022 | Criação do documento | Paulo Gotinjo e Thiago Gomes | Alex Gabriel e Matheus Costa|
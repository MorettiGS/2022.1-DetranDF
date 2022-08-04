# EP04 - Infração
A tabela abaixo ilustra o épico **Infrações**:

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US17 | RF12 | Consultar infrações | Ter acesso às informações sobre infrações | Must |
| US18 | RF14 | Consultar multas | Ter acesso as multas | Should |
| US19 | RF24 | Consultar pontuação associada ao condutor  | Ter acesso à pontuação | Should |
| US20 | RF33 | Transferir pontos de infração | Fazer a transferência dos pontos de infração| Should |
| US21 | RF34 | Transferir titularidade de multa | Fazer a transferência da titularidade da multa| Should |
| US22 | RF35 | Realizar pagamento de multa | Quitar uma multa | Should |
<h6 align = "center"> Tabela 1: Épico de Infrações</h6> 

## 1. US17
Eu, como **usuário** gostaria de **consultar infrações** para poder **ter acesso às informações sobre infrações**.

### 1.1. Critérios de avaliação
* Deve haver uma página que redireciona para a consulta das infrações associadas.
* O conteúdo deve ser mostrado de forma tabular.
* Deve conter a data, tipo e local das infrações.
* Deve conter no máximo 10 infrações por página.
* Deve ser possível fazer o download do documento em formato **PDF** da tabela completa das infrações.

## 2. US18
Eu, como **usuário** gostaria de **consultar multas** para poder **ter acesso às informações sobre multas**.

### 2.1. Critérios de avaliação
* Deve haver uma página que redireciona para a consulta das multas associadas.
* O conteúdo deve ser mostrado de forma tabular.
* Deve conter o valor da multa.
* Deve conter o prazo máximo para pagamento da multa.
* Deve conter no máximo 10 multas por página.
* Deve ser possível fazer o download dos boletos em formato **PDF** das multas.

## 3. US19
Eu, como **usuário** gostaria de **consultar pontuação associada ao condutor** para poder **ter acesso à pontuação**.

### 3.1. Critérios de avaliação
* Deve haver uma página que redireciona para a consulta das pontuações associadas.
* O conteúdo deve ser mostrado de forma tabular.
* Deve conter a pontuação acumulada associada ao condutor.
* Deve conter prazo para expiração da pontuação.

## 4. US20
Eu, como **usuário** gostaria de **transferir pontos de infração** para poder **transferir a pontuação da multa**.

### 4.1. Critérios de avaliação
* Deve haver uma página que redireciona para a transferência de pontos das multas associadas.
* Deve haver uma tabela com adição dos campos: 
  * Nome
  * CPF
  * RG
  * Email
  * Endereço
  * CEP
  * Número de pontos a transferir
* O usuário deve receber uma posição frente ao status da operação: sucesso ou falha.
* Deve ser possível consultar a data e a hora da solicitação.

## 5. US21
Eu, como **usuário** gostaria de **transferir a titularidade da infração** para poder **fazer a troca de titularidade da multa**.

### 5.1. Critérios de avaliação
* Deve haver uma página que redireciona para a transferência de titularidade das multas associadas.
* Deve haver uma tabela com adição dos campos: 
  * Nome
  * CPF
  * RG
  * Email
  * Endereço
  * CEP
  * Número de registro da multa a transferir
* O usuário deve receber uma posição frente ao status da operação: sucesso ou falha.
* Deve ser possível consultar a data e a hora da solicitação.

## 6. US22
Eu, como **usuário** gostaria de **realizar pagamento de multa** para poder **quitar a multa**.

### 6.1. Critérios de avaliação
* Deve haver uma página que redireciona para a pagamento das multas associadas.
* Deve conter um boleto para pagamento da multa, disponibilizado para download em **PDF**.
* Deve conter o prazo máximo para pagamento da multa.

## 7. Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 02/08/2022 | Criação do documento | Paulo Gotinjo e Thiago Gomes | Alex Gabriel e Matheus Costa |
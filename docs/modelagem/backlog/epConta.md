# EP01 - Conta
A tabela abaixo ilustra o épico **Conta**:

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... | Para poder... | Prioridade |
|:-:|:-:|:-:|:-:|:-:|
| US01 | RF1 | Criar conta | Ter acesso ao sistema | Must |
| US02 | RF2 | Realizar login | Acessar o conteúdo da plataforma | Must |
| US03 | RF42| Alterar email | Utilizar um novo email no sistema | Must |
| US04 | RF43 | Alterar senha | Utilizar uma nova senha para login | Must |
| US05 | RF45 | Cadastrar biometria | Acessar plataforma por biometria | Must |
| US06 | RF46| Cadastrar CPF/CNPJ | Usar como documento pessoal | Must |
<h6 align = "center"> Tabela 1: Épico de Contas</h6>

### 1. US01 - Criar uma conta
&emsp;&emsp;Eu, como **usuário**, gostaria de **criar conta** para poder **ter acesso ao sistema**.

#### 1.1. Criterios de aceitação
- Deve ler as informações informadas pelo usuário.
- As informações do usuário devem ser validadas.
- Deve salvar os dados do usuário.

### 2. US02 - Realizar login
&emsp;&emsp;Eu, como **usuário**, gostaria de **realizar login** para poder **acessar o conteúdo da plataforma**.
#### 2.1 Criterios de aceitação
- Deve ler as credenciais do usuário.
- Deve checar se as credenciais do usuário são validas.
- Deve liberar acesso do usuário à plataforma.
### 3. US03 - Alterar email
&emsp;&emsp;Eu, como **usuário**, gostaria de **alterar email** para poder **utilizar um novo email no sistema**.
#### 3.1 Criterios de aceitação
- Deve pedir que o usuário envie suas credenciais.
- Deve ler e checar se as credenciais são válidas.
- Deve pedir que o usuário envie o novo email.
- Deve alterar email do usuário.
### 4. US04 - Alterar senha
&emsp;&emsp;Eu, como **usuário**, gostaria de **alterar senha** para poder **utilizar uma nova senha para login**.
#### 4.1 Criterios de aceitação
- Deve pedir que o usuário envie suas credenciais.
- Deve ler e checar se as credenciais são válidas.
- Deve pedir que a nova senha e a confirmação da nova senha.
- Deve verificar se a nova senha é igual à confirmação de senha.
- Deve alterar a senha do usuário.
### 5. US05 - Cadastrar biometria
&emsp;&emsp;Eu, como **usuário**, gostaria de **cadastrar biometria** para poder **acessar plataforma por biometria**.
#### 5.1Criterios de aceitação
- Deve pedir que o usuário envie suas credenciais.
- Deve ler e checar se as credenciais são válidas.
- Deve salvar e vincular a biometria ao usuário.

### 6. US06 - Cadastrar CPF/CNPJ no sistema
&emsp;&emsp;Eu, como **usuário**, gostaria de **cadastrar CPF/CNPJ** para poder **usar como documento de usuário**
#### 6.1 Criterios de aceitação
- Deve pedir que o usuário envie suas credenciais.
- Deve ler e checar se as credenciais são válidas.
- Deve pedir que o usuário informe CPF/CNPJ.
- Deve verificar validade dos dados e vincular ao usuário.

## Histórico de Versão
| Versão | Data | Descrição | Autor | Revisor |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 01/08/2022 | Criação do documento | Thiago Gomes e Paulo Gontijo | Alex Gabriel e Matheus Costa |
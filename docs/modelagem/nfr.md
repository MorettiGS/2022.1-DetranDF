# NFR Framework
***

## 1. Introdução
NFR Framework, que traduzido do inglês significa Framework de Requisitos Não Funcionais, assim como seu nome diz, é um método de expressar e analisar requisitos não-funcionais que foi proposto por Chung na Universidade de Toronto em 1999. É caracterizado pela representação sistemática e global de NFR's, abordando de uma maneira qualitativa e orientada a processos.

Neste documento está contida análise dos requisitos não funcionais, que foi realizada com o auxílio deste framework.

## 2. Metodologia
Para a criação desta documentação, foi utilizada a metodologia do NFR Framework como forma de representar e analisar os Requisitos Não Funcionais através de usos de diagramas e tabelas, que foram elaborados a partir de análises das funcionalidades do aplicativo do Detran-DF.

## 3. Requisitos Utilizados
Na Tabela 1 estão listados os requisitos não-funcionais elicitados no projeto, que serão analisados e representados através da abordagem do NFR Framework.

<center>

| Número     | Requisito   | Técnica    |
|:------------:|-----------------|------------|
|RNF1|O aplicativo deve rodar nas versões mais recentes (até 5 anos) de Android e iOS|Introspecção|
|RNF2|O aplicativo deve ter uma latência máxima de 1000ms por requisição             |Introspecção|
|RNF3|O aplicativo deve estar disponível 24h                                         |Introspecção, Questionário|

</center>

<h6 align = "center">Tabela 1: Requisitos Não-Funcionais elicitados<br>Fonte: autores</h6>


## 4. NFR Framework

### 4.1. Definições

Os tópicos abaixo apresentarão uma breve descrição de alguns conceitos que permeiam o contexto do NFR Framework, com base na dissertação de mestrado de Reinaldo Antônio da Silva (2019).

#### 4.1.1. NFR Framework

O NFR Framework **é uma abordagem para representar e analisar Requisitos Não-Funcionais**. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão. Tais características incluem Requisitos Não-funcionais, prioridades e carga de trabalho. Esses fatores determinam a escolha de alternativas de desenvolvimento para um determinado sistema. (SILVA, 2019, p. 30)

#### 4.1.2. SIG - Softgoal Interdependency Graph

É um gráfico pelo qual o funcionamento do NFR Framework pode ser visualizado em termos da construção, elaboração, análise e revisão incremental e interativa de um gráfico de interdependência de softgoal. É este gráfico que registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências. (SILVA, 2019, p. 30-31)

#### 4.1.3. Softgoals

O Framework utiliza o conceito de softgoal. **Os softgoals são utilizados para representar Requisitos Não-Funcionais** e podem estar interrelacionados, expressando a influência de um softgoal em outro.

Silva (2019, p. 31, apud CHUNG, 2000) afirma que existem três tipos de _softgoals_:

- **Softgoals NFR**: representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto. Em sua notação são representados por **nuvens claras, com bordas simples**.

- **Softgoals de Operacionalização**: representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização. São representados por **nuvens com bordas mais grossas.**

- **Softgoals de Afirmação** (ou _Claim_): Eles servem como justificativa para apoiar ou negar a forma
como os softgoals são priorizados, refinados e os componentes são selecionados. Os softgoals de afirmação fornecem as razões para as decisões de desenvolvimento, facilitando a revisão, a justificativa e a mudança do sistema, bem como o aprimoramento da rastreabilidade. São representados por **nuvens com bordas tracejadas.**

### 4.2. Legenda

A legenda presente na Figura 1 abaixo servirá de apoio para a compreensão dos diagramas no tópico de [Resultados](#5-resultados).

<center>
<img src="..\..\images\nfr\nfr.jpeg">

</center>

<h6 align = "center">Figura 1: Legenda NFR Framework<br>Fonte: autores</h6>


## 5. Resultados

Este tópico abarca os gráficos SIG elaborados pelo grupo, que englobam os requisitos não funcionais elicitados e que podem ser vistos nas Figuras de 2 a 5 a seguir.

Os subtópicos estão separados de acordo com as classificações que os requisitos receberam, segundo o método FURPS+, como explicado no documento de [Especificação Suplementar](especificacao.md).

### 5.1. Suportabilidade
#### 5.1.1. Sem propagação

<center>
<img src="..\..\images\nfr\suportabilidade_sem.png">

</center>

<h6 align = "center">Figura 2: Diagrama de Suportabilidade sem propagação<br>Fonte: autores</h6>


#### 5.1.2. Com propagação

<center>
<img src="..\..\images\nfr\suportabilidade_com.png">

</center>

<h6 align = "center">Figura 3: Diagrama de Suportabilidade com propagação<br>Fonte: autores</h6>

### 5.2. Performance
#### 5.2.1. Sem propagação

<center>
<img src="..\..\images\nfr\performance_sem.png">

</center>

<h6 align = "center">Figura 4: Diagrama de Performance sem propagação<br>Fonte: autores</h6>

#### 5.2.2. Com propagação

<center>
<img src="..\..\images\nfr\performance_com.png">

</center>

<h6 align = "center">Figura 5: Diagrama de Performance com propagação<br>Fonte: autores</h6>

## 6. Referências Bibliográficas

> GARCIA, Gustavo. **NON-FUNCTIONAL REQUIREMENTS FRAMEWORK**:INFLUÊNCIAS NA QUALIDADE DE JOGOS DEENTRETENIMENTO COM TEMÁTICA ROLE-PLAYINGGAME. Disponível em: <http://r1.ufrrj.br/nuesgames/Gustavo.pdf>. Acesso em: 02/08/2022

> CHUNG, L. e NIXON, B., **“Using Non-Functional Requirements to Systematically Support Change”**. 1995.

> SILVA, REINALDO ANTÔNIO DA. **"NFR4ES: um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados"**. Universidade Federal de Pernambuco. 2019.

## 7. Histórico de Versão

|Versão|    Data    |    Descrição         | Autor        | Revisor |
|:----:|:----------:|:---------         --:|:------------:|:-------:|
| 0.1  | 02/08/2022 |Criação da página     | Arthur       | Alex e Matheus        |
| 0.2  | 03/08/2022 |Adição dos requisitos utilizados e NFR Framework     | Christian       | Alex e Matheus        |
| 0.3  | 03/08/2022 |Adição da metodologia | Arthur | Alex e Matheus      |
| 0.4  | 03/08/2022 |Adição das figuras 2-5    | Christian       | Alex e Matheus        |
| 0.5  | 30/08/2022 | Adição das Definições e correções no texto  | Matheus | Arthur        |

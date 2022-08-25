# Foward From

## 1. Introdução
O processo de pós-rastreabilidade de requisitos é eficiente quando for possível identificar os autores/responsáveis 
por cada etapa do ciclo de vida de um requisito, isso pode ser traduzido em informações que possibilitam reconhecer
a origem, motivo e relações com artefatos que determinado requisito possui. Para tal, existem uma série de técnicas na literatura que
podem auxiliar no desenvolvimento deste processo.

## 2. Metodologia
Cleland-Huang cita em uma de suas obras que rastreabilidade que, em seu fundamento, se refere ao potencial para relacionar dados
já existentes em algum artefato somado à habilidade de examinar estas relações. Isso induz em uma dependência 
em criar ligações navegáveis entre o conteúdo presente nos artefatos, que por ora poderiam estar desconectados.

Os principais conceitos relacionados a rastreabilidade são:

* Ligação de rastreamento (*Trace Link*): Associações semânticas entre duas entidades de rastreamento: fonte e destino.
* Entidade de rastreamento (*Trace Artifacts*): Unidade que pode ser agrupada por tipo e características de sua estrutura, como: histórias de usuários, léxicos e 
  cenários.
* Relação de rastreamento (*Trace Relation*): Consiste em todas a ligações de rastreamento criadas entre dois conjuntos de tipos específicos de artefatos.

A figura abaixo ilustra a relação entre os conceitos apresentados:

<center>

![img.png](../assets/conceitos-fowardfrom.png)

<h6 align = "center">Figura 1: Conceitos Foward-From</h6>
<h6 align = "center">Fonte: [1]Silva, Paulo Robson</h6>

</center>

Uma relação de rastreabilidade pode ser registrada em uma matriz de rastreabilidade, a qual pode ser traduzida como uma 
tabela que registra os artefatos, suas fontes e destino. A estratégia adotada por nosso grupo foi a de criação desta matriz,
 adaptando-a aos artefatos de modelagem já construídos anteriormente. Desta forma foi possível criar um método de rastreabilidade
eficiente e de fácil interpretação.

## 3. Requisitos

## 4. Referência Bibliográficas
> Sayão, Miriam. Leite, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. ISSN 0103-9741. Disponível em: https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf. Acesso em: 23 agosto 2022.

> [1]Silva, Paulo Robson. Modelo de Rastreabilidade de Requisitos Aplicada à Gestão de Projetos em Métodos Ágeis. Disponível em: https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjh3v692-D5AhXBD7kGHS4iCqEQFnoECC0QAQ&url=https%3A%2F%2Frepositorio.ufrn.br%2Fbitstream%2F123456789%2F22079%2F1%2FRobsonPauloDaSilva_DISSERT.pdf&usg=AOvVaw3kVtfOHf2xdQus2T78Y7r7&cshid=1661386665225071.
> Acessado em: 23/08/2022

> Cleland-Huang, Jane, Orlena Gotel, and Andrea Zisman. Software and systems traceability. Vol. 2. No. 3. London: Springer, 2012.

## 5. Histórico de Versão

| Versão | Data       | Descrição            | Autor                     | Revisor                |
|:------:|------------|----------------------|---------------------------|------------------------|
|  0.1   | 23/08/2022 | Criação do documento | Paulo, Christian e Thiago | Alex, Arthur e Matheus |



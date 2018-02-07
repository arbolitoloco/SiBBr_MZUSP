---

title: Campos da planilha de Diptera
theme: cayman
permalink: /planilha_diptera.html

---
# Campos da planilha de Diptera

# Orientações gerais
Abaixo estão listadas as explicações necessárias para cada campo na planilha, por ordem de aparecimento.
Para os campos fixos, descritos nas tabelas, use sempre o que aparece na primeira coluna, contendo o nome do campo. A coluna de Descrição lista dados equivalentes que podem aparecer nas etiquetas.

<!-- Screenshot campo final Specify -->


## Cataloger
Nome do agente catalogador, a pessoa que incluiu os dados na planilha, no seguinte formato: Sobrenome, Iniciais.
Exemplo: Laura Rocha Prado -> Prado, L. R.

## Cataloged date
Data na qual o espécime foi registrado, no formato DD/MM/AAAA.

## Catalog number
Número de tombo oficial do MZSP, fornecido pela técnica Camila Conti.

# Dados taxonômicos
Os seguintes dados devem ser conferidos antes da entrada na planilha, de preferência nos catálogos disponíveis para conferência. A entrada de dados incorretos nesses campos gerará árvores taxonômicas incorretas no banco de dados. Por favor tenha certeza de que as informações estão livres de erros antes de subí-las para o servidor. Os dados obrigatórios não podem ficar em branco na planilha.

Categoria | Obrigatório
------------ | ------------
Class | Sim
Order | Sim
Suborder | Sim
Infraorder | Não
Superfamily | Não
Family | Sim
Subfamily | Não
Tribe | Não
Genus | Sim
Subgenus | Não
Species | Sim
Species Author | Sim
Subspecies | Não
Subspecies Author | Não

## Determiner
Especialista que identificou o exemplar. Normalmente consta da etiqueta de identificação, quando presente. Entra na forma como estiver escrita.

## Determination Date
Data de identificação do exemplar que consta da etiqueta de identificação, se houver. Entra no padrão DD/MM/AAAA.

## Stage of Development
Normalmente será adulto (adult). Se você estiver lidando com imaturos, favor contatar seu supervisor/curador.


## Sex
Como a coleção de Diptera utiliza lotes com mais de um indivíduo, pode ser que ocorram indivíduos de sexos diferentes no mesmo lote. Assim, as opções desse campo são:

Sex  | Descrição
------------ | ------------
Male | Macho
Female | Fêmea
Both | Ambos
Unknown | Indeterminado

## Quantidades 
Indique a quantidade de indivíduos de fêmeas, machos, indeterminados, larvas, e pupas nos campos adequados (Qtde Macho, Qtde Fêmea, Qtde Indeterminado, Qtde Larva, Qtde Pupa), por lote. 
O campo Count1, mais adiante, tem uma fórmula que faz a contagem total desses campos. Se você perceber que o campo Count1 não está sendo atualizado, adicione uma fórmula de soma dos campos adequados. Se precisar de ajuda contate seu supervisor.

## Type Status
Apenas as seguintes cateogorias de tipos devem ser inseridas na planilha (em inglês):

Type Status | Descrição
------------ | ------------
Holotype | holótipo
Paratype | parátipo
Allotype | alótipo
Syntype | síntipo
Lectotype | lectótipo
Paralectotype | paralectótipo
Neotype | neótipo
Incipient Type | tipo incipiente (quando ainda não foi publicado ou não se tem certeza da validade)

Se o exemplar não for um tipo, o campo deve ficar vazio.

## Tipos de preparação (PrepType)
Apenas os seguintes métodos de coleta estão cadastrados na base de dados, sendo necessário utilizá-los com a seguinte grafia no campo adequado:

PrepType | Descrição
------------ | ------------
Pinned | Alfinetado
MEV | Metalizado para microscopia eletrônica
Alcohol | Quando não se sabe a proporção alcóolica
Alcohol 70% | Quando se sabe a proporção alcóolica
Alcohol 100% | Quando se sabe a proporção alcóolica
Dissected | Se há alguma parte do espécime, dissecada, em microtubo
On slide | Em lâmina
Fossil |

Se você encontrar um tipo de preparação que não está nessa lista, favor contatar seu supervisor/curador responsável.

Há espaço para até 4 tipos de preparação por indivíduo ou lote (linha na planilha). Assim, se um exemplar estiver alfinetado e também dissecado (com a terminália em um tubete com glicerina), o preenchimento deve se dar assim:

Preptype 1 | Count1 | Remarks1 | Preptype2 | Count2 | Remarks2 
------------ | ------------ | ------------ | ------------ | ------------ | ------------
pinned | 1 | | dissected | 1 | terminália acondicionada em tubete alfinetado juntamente ao espécime

O campo de Remarks se destina à explicação do tipo da preparação. O campo Count deve ser preenchido com o número de preparações por tipo de preparação. Assim, se houver duas lâminas preparadas a partir de um único indivíduo, a contagem do tipo On slide será 2.


## Origin 
Deve conter informação sobre coleção original de origem do material, quando for o caso. Normalmente trata-se de informação de Museus, Universidades ou Coleções Particulares.

## Donor
Deve conter informação sobre doadores do material, no caso de constar das etiquetas do indivíduo. Normalmente trata-se de um nome de uma pessoa (Ex-Coll. John Lane, por exemplo).

## Expedition
Contém informação sobre expedição de coleta. Exemplos comuns são "BIOTA-FAPESP" e "Exp. Dep. MZUSP".

## Verbatim Date
Deve conter a data de coleta no seguinte formato:
DD.MM.AAAA, onde o mês é dado em algarismos romanos.

Quando a data é um período, por exemplo 01-04/12/1999, a data verbatim ficaria 01-04.XII.1999.

No caso de ausência de informação de dia ou mês, omite-se. Assim, se a coleta foi feita em 01/1934 ela ficaria I.1934.

## Start Date, End Date
Deve conter a data de coleta no seguinte formato:
DD/MM/AAAA, onde o mês é dado em algarismos arábicos.

No caso de uma data única de coleta, repete-se a mesma informação em ambos os campos. 

No caso de período de coleta, Start Date deve ser a data inicial e End Date a data final.

No caso de ausência de informação de dia ou mês, substitui-se a informação por 00. Assim, se a coleta foi feita em 01/1934 ela ficaria 00/01/1934.

## Dados de Localidade (Continente, País, Estado, Cidade, Locality Name, Locality and Habitat Notes)

Os dados de localidade devem ser conferidos previamente (para verificar existência e atualidade do nome) e inseridos em português na planilha.

A tabela a seguir indica quais dados devem estar preenchidos:

Categoria | Obrigatório
------------ | ------------
Continente | Sim (em português)
País | Não (em português)
Estado | Não (no idioma que consta na etiqueta)
Cidade | Não (no idioma que consta na etiqueta)
LocalityName | Sim (no idioma que consta na etiqueta)

No caso da etiqueta não conter informação sobre localidade de coleta, ou dessa localidade não ser verificável, o campo do continente deve conter a opção "Sem Localidade".

O campo LocalityName não pode estar vazio. Ele deve, ou incluir a localidade de menor nível hierárquico disponível (bairro, Parque, Unidade de Conservação, vilarejo, etc), ou repetir a última informação disponível. Por exemplo, se soubermos apenas que o exemplar foi coletado no Brasil, o campo LocalityName deve incluir a informação "Brasil".

## Locality and Habitat Notes
Esse campo deve conter informações que não estão relacionadas a nomes de localidades. Por exemplo: mata, clareira, margem esquerda do rio, etc.

## Min e Max Elevation
Dados de altitude (em metros). Não é necessário colocar a unidade métrica, apenas os números.

## Latitude e Longitude
Dados geográficos, quando houver, no padrão disponível (o banco de dados normalmente aceita todos). 
Ao utilizar o padrão GSM (Graus, Minutos, Segundos), tenha certeza de que os caracteres especiais usados são os corretos. Isso pode ser um problema na importação de dados para o Specify. 
O caractere de grau (° - atalho no Windows de teclado Português Brasilieiro Alt + 0176, padrão unicode U+00B0: Grau), por exemplo, não deve ser confundido com o caractere ordinal masculino (º - atalho no Windows de teclado Português Brasilieiro Alt + 0186, padrão unicode U+00BA: Ordinal Masculino). 
A mesma atenção deve ser dada aos caracteres para minutos (', padrão unicode U+0027: Apóstrofo) e segundos ('', dois apóstrofos), que não devem ser confundidos com aspas.

## Collectors
Coletores informados na etiqueta, como estiverem citados, mas normalmente no padrão Primeiro nome e sobrenome.

## Métodos de coleta (Method)
Apenas os seguintes métodos de coleta estão cadastrados na base de dados, sendo necessário utilizá-los com a seguinte grafia no campo adequado:

Method | Descrição
------------ | ------------
Aspirador | 
Ativa | Coleta manual
CDC Trap |
Luminosa | Luz, Light
Malaise |
McPhail |
Moerick |
Prato| Bacia
Shannon |
Van-Someren |
Varredura | Sweeping

Se você encontrar um método de coleta que não está nessa lista, favor contatar seu supervisor/curador responsável.

## Número de Campo
Se houver informação de número de campo na etiqueta, ela entra aqui. Serve, por exemplo, para número de Malaise, trilha, códigos diversos não identificáveis.

## CO_REMARKS
Observações quaisquer sobre o indivíduo/lote. Aqui podem entrar antigos números de tombo, observações que estejam na etiqueta e que pareçam adequadas, outras informações gerais.

<!-- ## Telas para mapeamento dos campos no Specify
![Tela 1](/images/coleoptera_tela_map1.png)
![Tela 2](/images/coleoptera_tela_map2.png) -->
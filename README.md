# O projeto
O projeto Contribuição do Museu de Zoologia da USP à implementação do [SIBBR](http://www.sibbr.gov.br/) - Sistema de Informação sobre a Biodiversidade Brasileira, financiado pelo CNPq (processo 401899/2014-4) tem como objetivo digitalizar parte das coleções biológicas depositadas em uma das mais importantes instituições de pesquisa do mundo.

## A importância das coleções biológicas
As coleções biológicas são assembleias ordenadas de espécimes devidamente preservados para estudos. Além do valor cultural e científico, o valor material propriamente dito disponível nessas coleções é imensurável. As coleções entomológicas abrigadas no Museu de Zoologia da Universidade de São Paulo representam um dos maiores acervos biológicos neotropicais do mundo, com mais de dois milhões de exemplares contabilizados.
Os membros desse projeto têm a responsabilidade de capturar os dados biológicos que acompanham os exemplares do acervo das coleções entomológicas do MZUSP e armazená-los em um banco de dados. Os bolsistas devem inserir informações de qualidade no banco de dados, de forma a garantir a sua confiabilidade científica. Além disso, entre o material cadastrado, encontram-se inúmeros exemplares-tipo, que carregam consigo permanentemente nomes científicos. Por isso o tratamento desse material é feito de maneira extremamente cuidadosa e dedicada.
<hr>

# A interface do banco de dados
O programa que gerencia os dados originados a partir da digitalização dos espécimes é o [Specify](http://specifyx.specifysoftware.org/welcome-to-specify-6-desktop-application/). **Atualmente usamos a versão 6, que não deve ser atualizada até o fim do projeto**. Portanto, se, ao fazer login no sistema, o Specify informar que há uma nova atualização, por favor ignore esse alerta e continue normalmente com o seu trabalho.

## Dúvidas sobre o Specify
Por favor leia a [documentação](http://specifyx.specifysoftware.org/documentation/) ou os [vídeos de ajuda](http://specifyx.specifysoftware.org/specify-project-helpcasts/) do Specify 6 para sanar a maioria das dúvidas encontradas na utilização do programa. Dúvidas pontuais podem ser resolvidas na seção [Outras Informações](#outras-informaes) desse repositório.
<hr>

# Protocolo de digitalização dos espécimes
1. Separar material a ser trabalhado.
2. Preparar as etiquetas de número de tombo, que serão adicionadas ao exemplar digitalizado. Usar a [planilha modelo adequada](#planilhas) para fazer novas etiquetas. 
3. Separar o exemplar a ser digitalizado e retirar as suas etiquetas. Posicionar as etiquetas juntamente à etiqueta de tombo que será associada ao exemplar. Fotografar todas as etiquetas do exemplar juntas. Vide exemplo: 
![Etiquetas fotografadas](https://raw.githubusercontent.com/arbolitoloco/sibbr_mzusp/master/5170_Artemita_brasiliana_exemplo.jpg)
4. Devolver as etiquetas ao exemplar de origem, na mesma ordem em que elas se encontram, que segue normalmente segue o padrão (de cima para baixo): 
   1. etiqueta de localidade, 
   2. etiquetas de outras coleções, 
   3. etiqueta de determinação, 
   4. etiqueta de número de tombo. 
**Atenção: essa etapa é IMPORTANTÍSSIMA. É imprescindível que as etiquetas fiquem associadas aos exemplares de origem. Se as etiquetas forem trocadas, toda a informação científica é perdida e inutilizada. Por favor seja responsável e cheque várias vezes se você está devolvendo as etiquetas para os exemplares corretos.**
5. Anotar o número de tombo e a quantidade de indivíduos do lote, quando for o caso (para coleções que usam lotes). Para coleções que usam lotes: fazer as etiquetas repetidas de número de tombo, usando o [modelo adequado](#etiquetas) e associá-las aos espécimes correspondentes.
6. Prestar atenção ao estado de conservação do material: ao encontrar espécimes muito danificados, fungados, alfinetes com oxidação, ou qualquer outro tipo de dano, favor tomar nota e me avisar, para que eu possa encaminhar o material para recuperação.
7. Fazer upload das imagens da câmera/celular para o computador. Renomear as imagens de acordo com o número de tombo de cada uma. [Utilizar o software XnView para facilitar essa etapa (ver tutorial)](#tutoriais).
8. Usar as imagens das etiquetas e as anotações para dar entrada na planilha de dados.
9. Ao acumular um número razoável de exemplares tombados (a partir de 500 exemplares, por exemplo), fazer o [upload da planilha para o Specify (ver tutorial)](#tutoriais).
<hr>

# Outras informações

## Tutoriais
* [Como usar o XnView para renomear arquivos de imagem em lote](https://arbolitoloco.github.io/sibbr_mzusp/xnview.html)
* [Como fazer upload da planilha para o Specify]() - Faltando

## Explicação para campos de planilha de cada coleção

## Arquivos modelo

### Planilhas
* [Blattodea]() - Faltando
* [Coleoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/planilha_modelo_Coleoptera.xlsx)
* [Coleoptera Imaturos]() - Faltando
* [Diptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/LRP_Specify_modelo_Diptera.xlsx)
* [Mantodea]() - Faltando
* [Orthoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/KMK_Modelo_Orthoptera.xls)
* [Trichoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/KMK_Modelo_Trichoptera.xls)

### Etiquetas
* [Blattodea](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiquetas_geral.xls)
* [Coleoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiquetas_geral.xls)
* [Coleoptera Imaturos](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiqueta_Coleoptera_Imaturos.xls)
* [Diptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/etiquetas_modelo_Diptera.doc)
* [Mantodea](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiquetas_geral.xls)
* [Orthoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiquetas_geral.xls)
* [Trichoptera](https://github.com/arbolitoloco/sibbr_mzusp/raw/master/modelos/modelo_etiquetas_geral.xls)
<hr>

# Catálogos e informações taxonômicas online

### Gerais
* [ITIS - Integrated Taxonomic Information System](http://www.itis.gov/)
* [Catálogo Taxonômico da Fauna do Brasil](http://fauna.jbrj.gov.br/fauna/listaBrasil/ConsultaPublicaUC/ConsultaPublicaUC.do)
* [Nomenclator Zoologicus - Rod Page](http://iphylo.org/~rpage/nz/index.php)
* [Zoological Record](http://apps-webofknowledge.ez67.periodicos.capes.gov.br/ZOOREC_GeneralSearch_input.do?product=ZOOREC&SID=3D26X5MiNyYakccO6ZM&search_mode=GeneralSearch) - Obs.: Só funciona dentro da USP

### Diptera
* [Diptera Nomenclator](http://www.diptera.org/NomenclatorSearch.php)
* [Orthoptera Species File Online](http://orthoptera.speciesfile.org/HomePage/Orthoptera/HomePage.aspx)
<hr>

# Dúvidas comuns
- Não consigo ler o que está escrito na etiqueta de coleta. O que faço?
  - No campo apropriado de comentários (isso depende da sua tabela, geralmente é o campo de "remarks" da localidade ou do objeto), escreva algo como "etiqueta de coleta ilegível", deixando os campos de localidade vazios.
 
- Não encontrei o nome científico nas fontes de dados às quais tenho acesso. E agora?
  - Tente procurar pelo nome no banco [Zoological Record](http://apps-webofknowledge.ez67.periodicos.capes.gov.br/ZOOREC_GeneralSearch_input.do?product=ZOOREC&SID=3D26X5MiNyYakccO6ZM&search_mode=GeneralSearch). Veja se encontra alguma informação referente ao nome, à descrição original ou outro trabalho. Se mesmo assim não encontrar o nome, anote-o e peça ajuda para mim ou para o curador responsável pela coleção em que você está trabalhando.
   
- Fiz uma pesquisa e não consegui descobrir onde fica a localidade citada na etiqueta de coleta. Como preencho a planilha?
  - Deixe os campos que você não conseguiu identificar em branco. Preencha apenas os referentes à localidade menor que você tiver. Por exemplo, se a etiqueta diz apenas "Brasil, Fazenda Estrela", preencha apenas os campos de País e LocalityName.

- Como preencho as datas de coleta na planilha?
  - O padrão seguido pelo Specify para as datas (Start Date/End Date) é o seguinte: quando não há dias ou meses, substitui-se os números por 00 e mantêm-se o formato DD/MM/AAAA. Assim, se a data da etiqueta for VII.1973, na planilha a data será: 00/07/1973 (mesma data em Start e End Date). Se a data da etiqueta for apenas o ano, por exemplo 1901, na planilha a data será: 00/00/1901. 
  
- Uma parte do exemplar quebrou ou já estava quebrada na caixa. Como conserto?
  - Anote na gaveta que há um exemplar quebrado e peça ajuda para mim. Vou encaminhar o exemplar para o técnico responsável para conserto, quando possível.
  
- Preciso de mais etiquetas de número de tombo. O que faço?
  - Se você não tiver alguém que faça as etiquetas da sua coleção, faça as etiquetas seguindo o [modelo adequado](https://arbolitoloco.github.io/sibbr_mzusp/#etiquetas). A impressão deve ser feita em papel cartão, disponível com os técnicos de cada coleção ou com a Ana Vasquez (para as coleções que não tem técnicos).
 
- Como acesso o meu termo de concessão da bolsa?
  - Entre na [Plataforma Chagas do CNPq](http://carloschagas.cnpq.br/), clique em "Outros Bolsistas" e faça login com o seu CPF e senha cadastrados (os dados são os mesmos utilizados na Plataforma Lattes). No menu à esquerda, clique em "Termo de Concessão" e depois clique no documento relacionado para visualizá-lo.

  





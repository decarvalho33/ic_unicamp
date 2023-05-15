O problema atual é metodos pra estudos de pangenoma

Ao mesmo tempo que é fundamental obter os insights certos a partir de metodos de pan-genoma, QUE SÃO NECESSÁRIOS!!!, MAS ESTES DEPENDEM DOS MÉTODOS, 

então o meu trabalho é estudar os métodos. e de quebra ver se consigo ter bons resultados pro caso do bioetanol brasileiro.



ARTIGO FODA: MODELING BIOLOGICAL PROBLEMS IN COMPUTER SCIENCE: A CASE STUDY IN GENOME ASSEMBLY.
na verdade toda essa palestra é foda.. https://www.youtube.com/watch?v=yaxFoelYf4o
nela explica namoral que usa-se grafos pra fazer assemblies e que isso n é facil etc..

------
#perguntas promissoras

1- então assembly com s288c, ou só usando gene de ref normal, é realmente tipo se não tem no s288c DESCARTA, ou considera mutação???? pq se descartar então é obvio que precisa de pangenoma......... 
	ANÁLISE A PARTIR DA PERGUNTA: 
pq se realmente for isso ai da minha pergunta, entao pode ter muitas ORFs que não pegam usando gene de ref. mas será que é isso mesmo??? uma forma de saber é aplicando o pipeline de pegar as orfs e comparar com elas mesmo pra ver se tem análogas e ver quais mais tem, enquanto também 
então os outros metodos de assembly que pegam orfs que nao tem no s288c

2- 'DE NOVO' REALMENTE SÓ DÁ DADO MERDA?????
	ANÁLISE
Pq se for assim então já descarta muiiiito metodo de pangenoma.. pra isso depois que eu pesquisar no youtube é bom até ler a discussao/resul do song pq ele fez muito 'de novo'com os orf nao-ref
- https://www.illumina.com/Documents/products/technotes/technote_denovo_assembly_ecoli.pdf
conclusão: NÃO DA MERDA, dá de boa pra usar 'de novo' e os resultados, q dá pra citar e tao nesse link, são bons. Só precisa que os short reads sejam bem filtrados. pega essas aspas:


3- os genomas são sequenciados como dos 33 lá mais outros que eu consiga pegar?? isso é boa pergunta pro Andreas.. 
	ANÁLISE:
Daí, eu consigo ver quais métodos de pangenoma que eu estudei daria pra aplicar.. então por isso q vale a pena escrever sobre todos

4- quanto às tecnologias, o Ilumina faz mts short-reads, o PacBio HiFi produz longreads com alta resolução que são sequenciados SEM GEN DE REF pelo Hifiasm, Nanopore tbm produz long-reads mas n é tao acurate não. 

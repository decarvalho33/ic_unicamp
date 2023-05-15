--------
CONCEITOS GRANDES

1- Shotgun genome sequencing

	Aparentemente é a técnica que usa o assembly e scaffolding pra chegar em um genoma completo a partir dos reads. Começa filtrando:
- filtração inicial
	Isso é feito sempre filtrando primeiro os reads (os que tem muitos nucletídeos não indentificados são descartados, normalmente). Depois, parte pro assembly pra ir juntando os reads em pedaços de genoma maiores.
- Genome Assembly:
	Tem duas formas de fazer o assembly, usando genoma de referência ou por superposição, que depois irão formar os pedaços de genomas maiores chamados de contigs!
	Com genoma de referência, quando bater um pedaço no genoma de ref aí vai formando os contigs e as pequenas variações são computadas (SNPs,   ) 
	Com superposção, TAMBPEM CHAMADOS DE 'DE NOVO' só pega os overlaps dos reads.
	Depois pegamos esses configs e formamos finalmente o DNA sequenciado, na técnica de Scaffolding.
- Scaffolding
	Aqui quando temos short-reading não tem pra onde correr, tem que adicionar NNNNN (nucleotideos indefinidos pra formar o DNA). 
	Mas quando tem long-read aí dá pra pegar os long reads que batem com os ends dos configs e juntar lá onde faltou e gera mais perfeitinho o DNA. 
- MAS AINDA FALTA FAZER O GENOME ANNOTATION: QUE SÃO TECNICAS PRA IDENTIFICAR CARACTERÍSTICAS DO GENE!

1- resumo do 1: 1- https://app.jove.com/science-education/12023/genome-annotation-and-assembly

2- Genome Annotation

	Aqui que temos características do gene já 'completo'. Existem duas annotations pra poder pegar as informações fundamentais, que são as estruturais e as funcionais.
	As estruturais 
	Já as fucionais 




----------
CONCEITOS PEQUENOS

1- SVs- Structural variations

	São variações nos genes mesmo, sem se preocupar com caracteristicas fenópticas

2- CNVs- Copy number variants

	É um tipo de variação, assim como insertion ou deletion. Só que aqui tem q estar relacionado com cópias de um gene e tal

3- CNPs- Copy number polymorphisms

	São CNVs que são identificadas em vários indivíduos: "If present at >1% in a population a CNV may be referred to as copy number polymorphism (CNP)"


------------------------------------
ESTUDOS COMPLETOS

1- O que são de fato pangenomas e como construílos? 

	São 
	há 3 formas de implementações de pan-genomas, ou seja, estudos comparativos entre os genes.

1- collection



2- presence absence variation

def e met:
	Divide-se o genoma usando clusters [que podem variar os métodos? ou é sempre por gene prediction?] no pan-genomeS.cerevisae foi clusters das proteínas que os genes poderiam codigicar usando CD-HIT. 
	A divisão é em: core (parte comum à mais de 95% dos sequenciamentos) character genes (de 5-95%) e acessory pool (menos de 5%).
	
ex e resul:
	No profdoandreas usou, 
	No song usou, pra poder 

3- graphical representation

	

-------------------------------
1.  'de novo'?


2. 

	





Antes disso que ta em baixo ainda, eu preciso fazer um teste de qualidade pra ver se vai dar pra fazer o pangenoma. Então só desenvolver um pipeline de controle de qualidade pra cereviiae igual nature fez ora oangenoma já seria uma ic. Pra averiguar isso, eu preciso:
1- ler as dificuldades de filtração do pangenoma pra cerevisiae o artigo + artigo 1011 genomas pra ver as merda q deu + artigo unesp? ou não esse ultimo
2- comparar com o que fizeram no pangenoma humano

no artigo do "draft human pangenome" eles conseguiram usar o pangenoma pra sequenciar as short-read, E OS RESULTADOS FORAM MELHORES. então, eu leio como está os sequenciamentos de short read usando SC88C e vejo se fosse pangenoma seria melhor. O que fazer pra chegar nisso:
0- ler como é feito sequenciamento normal hj em dia, desde USO DE REFERENCIA S288C!! até pacbio/nanopore/de novo
1- ler como é o pangenoma
2- ler como usar o pangenoma pra sequenciar
3- ESCREVER OS MÉTODOS PRA CRIAR UM PANGENOMA DE LINHAGENS DO BIOETANOL, tudo a partir de sequências já feitas usando shotgun mesmo!
4- ler 1011 genes de S.cerevisiae + artigo unesp + outros 3 artigos de sequenciamento de S.cerevisiae pra ENCONTRAR BRECHAS NO SEQUENCIAMENTO OU NO ANNOTATION (na vdd seria melhor se o foco fosse apenas em sequenciamento - assembly -) que poderiam ser corrigidas usando o meu pangenoma.



-------- ARTIGOS:
ARTIGO "A draft human pangenome reference"

# OBS IMPORTANTES:
1- os sequenciamentos são long-read e muito bem feitos. LOGO, NÃO SEI SE VOU CONSEGUIR FAZER USANDO SÓ SHORT-READ.

2- ter usado o telomere-to-telomere [é long-read esse então né?] pra sequenciar short-reads foi MUITO mais produtivo do que usar o GRCh38 (ref 1,4).

# MÉTODOS

-OBS:
1- eles fizeram 'alignments of the assemblies??'


# RESULTADOS

1- USARAM O DRAFT PANGENOME PRA COMPARAR COM SHORT READ E TIVERAM MELHORES RESULTADOS
 Using our draft pangenome to analyse short-read
data reduced small variant discovery errors by 34% and increased the number of
structural variants detected per haplotype by 104% compared with GRCh38-based
workflows, which enabled the typing of the vast majority of structural variant alleles
per sample
-OU SEJA:
c



-----------
ARTIGOS QUE TENHO QUE LER E O MOTIVO:

1- Esses 3 daqui pra baixo:
13. Garrison, E. et al. Variation graph toolkit improves read mapping by representing genetic
variation in the reference. Nat. Biotechnol. 36, 875–879 (2018).
14. Eizenga, J. M. et al. Pangenome graphs. Annu. Rev. Genomics Hum. Genet. 21, 139–162
(2020).
15. Wang, T. et al. The Human Pangenome Project: a global resource to map genomic diversity.
Nature 604, 437–446 (2022).
- motivo: eles tem a chave pra entender a estutura de dados do pangenoma e ainda melhor, podem conter como usar ele de referencia (operaçlão de recuperar dados lá pra comparar durante o assembly de reads)

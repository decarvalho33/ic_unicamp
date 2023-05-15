------------------------------------
artigo Nielsen

#resumo do que fizeram


#aspas fortes


------------------------------------
artigo song
Song G, Dickins BJA, Demeter J et al. AGAPE (Automated Genome
Analysis PipelinE) for pan-genome analysis of Saccharomyces
cerevisiae. PLoS One 2015;10:e0120671

o q eles fizeram de bom método:

1- pipeline pra extrair só o q não é do s288c a partir de READS!:
Sequence reads for each strain in FASTQ format were aligned to the S. cerevisiae reference ge-
nome using Burrows-Wheeler Aligner (BWA) (‘bwa aln-q 15-l 35-k 2-n 0.04-o 2-e 6-t 1’ and
‘bwa sampe’) [44]. Unmapped reads were extracted using SAMtools programs ‘samtools sort’,
and ‘samtools view’ (with parameter settings of ‘-u-f 4-F 264’, ‘-u-f 8-F 260’, and ‘-u-f 12-F
256’). Unmapped reads were assembled using ABySS with the same parameters as set in the
whole genome assembly. The resulting contigs were aligned to the reference genome to confirm
that they were not present in the reference. Contigs shorter than 300 bp, which is the length
cutoff for predicted ORFs, were discarded because short contigs are more likely to be derived
from reads of low quality, composed of ambiguous bases, or represent spurious ORFs. We con-
sider the remaining contigs as new sequences that are not in the reference. These additional se-
quences were then aligned to their own strain’s whole genome assembly using LASTZ (version
1.03.02, with parameters ‘T = 2 Y = 3400’) to find the corresponding genomic region of each
additional sequence in the whole genome assembly. We created a set of non-reference ORFs
from each strain by collecting ORFs annotated for these additional genomic regions in the
whole genome assembly

#resumo métodos objetivos e implememntações pangenoma 

assembly and annotation:
- Eles fizeram ASSEMBLY de reads usando 'de novo' e um scaffolding lá pra chegar no gene final. Depois, no genome ANNOTATION, eles fizeram predição de proteínas (ORFs) pra pegar os genes. 

Identifying novel sequences and ORFs relative to S288C
- Eles pegaram OS READS e viram quais ORFs desses não tinham no S288C. Depois fizeram ASSEMBLY SÓ COM ORFs NÃO-REFS, DEPOIS ALINHARAM COM OS ASSEMBLEDS 'DE NOVO' E VIRAM ONDE TAVA ESSES ORFS DENTRO DO SEQUENCIAMENTO.

catching homologues non-refs ORFs in all ORFs and register
- Eles simplesmente PEGARAM TODAS AS ORFS QUE N TINHAM NO S288C E COMPARARAM ENTRE ELAS PRA VER SE BATIAM. AS QUE BATIAM ELES FIZERAM UM

#aspas fortes
PQ NÃO DA PRA FICAR SÓ NA S288C:
- Genomics studies using the standard S288C yeast reference ge-
nome have produced many informative and interesting results [13]. However, our understand-
ing of yeast genetics and systems biology will widen and deepen if we can integrate new data
into a pan-genome model to account for a greater proportion of the genetic and phenotypic
variation exhibited by the global population of S. cerevisiae. A pan-genome is defined as the set
of all genes in a species [14], and can be constructed from the union of gene sets over all S. cerevisiae strains.

- To assign strain-specific functional annotations, we identi-
fied genes that were not present in the reference genome. We classified these according to
their presence or absence across strains and characterized each group of genes with
known functional and phenotypic features.


TRANSIÇÃO DE DADOS ENTRE PROCARIOTO PRA EUCARIOTO:
Pipelines for the pan-genome analysis of bacteria have been developed such as PGAP [15], but
these are not suitable for eukaryotic genomes, even for unicellular eukaryotes such as yeasts,
which exhibit more complex gene structures and non-genic regions than prokaryotes.




------------------------------------
artigo mccarty e fritz
McCarthy CGP, Fitzpatrick DA. Pan-genome analyses of model
fungal species. Microb Genom 2019;5:e000243


#resumo do que fizeram


#aspas fortes
PQ GENOMA DE REF TEM Q MUDAR PRA PANGENOME:
Many fields of eukaryote functional and comparative geno-
mics rely on the use of curated reference genomes intended
to be broadly representative of a given species. Regardless of
their quality, reference genomes do not and cannot contain
all genetic information for a species due to genetic and
genomic variation between individuals within a species [1].
To account for such variation, it has become increasingly
common to refer to species with multiple genomes
sequenced in terms of their ‘pan-genome’, which is defined
as the union of all genes observed across all isolates/strains


------------------------------------
artigo gallone

#resumo do que fizeram


#aspas fortes



------------------------------------
artigo Peter (1011)

#resumo do que fizeram


#aspas fortes



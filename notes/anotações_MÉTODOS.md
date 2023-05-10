#ideias e questionamentos

- cara eu tenho pra me basear:
1. o método do profdoAndreas
2. pangebook fungi
3. ver os métodos da unesp e encontrar lacunas pra ver onde entrariam o pangenoma nessa história, já que eles (i) juntaram dois genes em um só [ler sessão ASSEMBLY AND MANUAL CURATION OF H3 AND H4 GENOMES, MT IMPORTANTE] , (ii) compararam os genes que não bateram com o S288C e OS QUE NÃO BATERAM FORAM CATALOGADOS.


esse gene de ref não pode ser só de um ou poucos individuos pq se não pode dar caô igual o grave caô de remedio só pra branco. Mas apesar de se tratar de leveduras não é tão diferente até pq já foi dito que leveduras são semelhantes aos genes humanos!




#------- OS MÉTODOS DE PANGENOMAS PARA A S. CEREVISIAE (FOCO NO ARTIGO DO NIELSEN) SÃO OS MESMOS ENCONTRADOS ATUALMENTE PARA O DESENVOLVIMENTO DE PANGENOMAS? 

- fortes candidatos: PGAP, ITEP (que classificam baseado em predições de proteinas) e Panseq (que classifica pelo próprio sequenciamento)


terei que representar usando grafos e usar BLAST + MCL


PGAP (usa grafos):
The software uses two methods to calculate all of the
analyses: (i) the GF method to detect homologous genes, and
(ii) the MP method to detect orthologous genes.
The GF method is based on the protein BLAST and MCL
algorithms. All of the protein sequences are brought to-
gether, and protein BLAST is performed; the results are fil-
tered and clustered using the MCL algorithm [58, 61].
The MP method is based on two algorithms: (i) In-
paranoid to search orthologous and parologous genes us-
ing BLAST. Then, the pairwise ortholog clusters are
moved to (ii) MultiParanoid, which was specifically de-
veloped to search for gene clusters among multiple strains
[58, 62-64].

ITEP (gostei desse kkkk): python e Bash + SQLite database.

Panseq: BioPerl




#--------COMPARAÇÃO COM GENES DE REFERÊNCIA - FOCO NO ARTIGO DELE E UNESP COMPARANDO COM S288C

-- geral:
- então na unesp vi que é isso mesmo que ele me falou, vai fazendo a predição dos genes sequenciados comparando com o S288C

-- ANTES da predição:
- ELES JUNTARAM DOIS SEQUENCIAMENTOS, que eles chamaram de H3 e H4 - ambos da mesma linhagem (PE-2) -, e chamaram o assembled de 
- 

-- DURANTE a predição:
-
-OS GENES QUE NÃO BATERAM COM O S288C ELES CATALOGARAM!! ESSES 'FILHOS SEM PAI' AÍ PODEM SER INTERESSANTES EMMMM
- eles desconsideraram genes com tamanho menor que 150bp (ué?), os relacionados com Ty elements [?], e os de regiões teloméricas [VER ARTIGO DO PANGENOMA HUMANO QUE FALA QUE OS GENES DESSA REGIÃO PODEM SER INTERESSANTES], pois são mt repetitivos.
- 




#--------CH 1 PANGEBOOK

- Cricks's central dogma: 

conceitos importantes que não sei:
- pipeline
- novel



então a ideia central do projeto é fazer o pangenoma¹ das leveduras pra conseguir melhor produtividade das leveduras usando a técnica da UNESP². 
	Por que? 
	1- Leveduras e o potencial pra humanidade:
	pois leveduras tem uma história fudida³, e podem mudar o mundo⁴. Se descobrir como melhorar muito⁵ leveduras a ponto de suprir completamente a demanda energética, será a descoberta do século.
	Um meio de fazer isso 


#fortes ideias IDEIAS

- então o caô todo de fazer o pangenoma é que é difícil ter uma estrutura de dados capaz de guardar toda essa informação, que envolve o gene de referência e as possíveis variações?
---- se for isso, a solução é graph pangenomes .

- como fica ruim fazer comparações genicas usando só sequenciamentos do tipo short-read⁶, usa-se agora comparação usando long-read⁷. O problema disso é que pede estrutura de dados melhor já que é muito dado pra comparar etc.. Mesmo problema abordado extensivamente no pangenoma.md. 


#fortes ideias ESTRUTURA

-GERAL: biocombustível é uma questão. Leveduras são uma solução. Leveduras tem histórico forte na humanidade, hj em dia principalmente, mas precisa de GM. GM com leveduras tem muitos pros e contras, em que todos esses levam em comum que deve ser um estudo mais completo possível, e isso é amplificado por estudos genômicos comparativos. Esses estudos, levando em consideração o pangenoma humano, são disruptivos de tão bom q são mas precisam ser completos se não é intrinsecamente inconclusivo (isso se tratando de uma linhagem apenas). Só que pra leveduras seria mais interessante estudar isso com várias linhagens, dado o histórico da mesma de termos certas linhagens que são melhores pra produtividade e tal. Um estudo comparativo com de linhagens diferentes é o da UNESP. Porém eles cometeram o erro de não expandir para vários organismos da mesma linhagem (o erro que incentivou o pangenoma tlg??????) e a partir daí vem a ideia central do projeto: PROPOR UM PANGENOMA APLICÁVEL A COMPARAÇÃO DE VÁRIAS LINHAGENS!! e isso é um desafio de estrutura de dados e bioinformática.     

- fazer uma seção na introdução só pra pangenoma e me guiar pelas anotações do artigo do pangenoma, COLOCAR A IMAGEM 'VISUALIZING VARIATION' QUANDO FOR FALAR DOS GRAPH-PANGENOMES na parte de estrutura de dados para este.
	
	
NOTAS:
1- ler anotações pangenoma pra entender como é importante ter pangenoma
2- [preciso entender o método da UNESP]
3- ascenção das leveduras anotações zap 
4- é bom adentar nisso pq é um baita de um objetivo foda pra cnpq aceitar meu projeto.
5- o problema de só aplicar bioetanol hj em dia é que os investimentos pra começar com isso gasta mais energia do que irá produzir, então meio que não é nada lucrativo e n da pra fazer isso no livre mercado do capitalismo global, ainda mais hj em dia que os acordos ecológicos entre os principais países do setor energético são sempre ignorados de certa forma.
6- Roche 454 and emerging Illumina technologies (isso no artigo unesp) e tem mais no artigo pangenoma se pá no markdown dele vai ter anotado
7- PacBio/Oxford Nanopore (artigo unesp), esse lindo excerto:
/long-read
sequence data (e.g., generated using PacBio/Oxford Nanopore
technologies) can better resolve these repetitive regions and
have been used to improve the chromosomal positioning of
telomeres, solo-long terminal repeats (solo LTRs), complete Ty
transposable elements, and more importantly, of multi-paralog
gene families (McIlwain et al., 2016; Istace et al., 2017; Salazar
et al., 2017; Yue et al., 2017). \


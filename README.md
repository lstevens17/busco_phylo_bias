# Are BUSCO scores phylogenetically biased? 

## Motivation 
We recently received reviews for our manuscript on [the genome of *C. bovis*](https://www.biorxiv.org/content/10.1101/766857v1) and one of the reviewers asked why the BUSCO completeness score was only 94.2% with a further 4.6% of BUSCO genes being fragmented despite the chromosome-scale assembly. They suggested that this may due to remaining sequencing errors which are leading to frameshifts and therefore fragmented gene models. 

So what's going on? 

## Methods
We ran BUSCO (v3.0.2) using ‘nematoda_odb9’ dataset the across all 56 *Caenorhabditis* genome assemblies. 

## Results
BUSCO scores range from 78.1% (*C. angaria*) to 98.7% (*C. elegans* and *C. nigoni*) (Figure 1). Most assemblies are highly-complete with 95% of species having a BUSCO score above 90% and 71% having a score above 95%. The four best assemblies include *C. elegans* (obviously) and three long-read assemblies (from Erich Schwarz and John Wang). 

*C. bovis* comes in 45th of 58 species. Not looking great, is it? 

















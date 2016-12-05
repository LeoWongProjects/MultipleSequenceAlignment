# MultipleSequenceAlignment

## Abstract
The genomes of all organisms contain the information required to define unique phenotypic traits and morphology distinguishing individuals from one another, and from other species. The genetic code composed of immensely long chains of nucleotides are interspersed with various distinct regions such as exons, introns, genes, enhancers, promoters and so on. Technology modernizationand computational advancement have brought major improvement in sequencing efficiency, as it has been recently possible to sequence the entire human genome. Applications of sequencing techniques include de novo sequencing, where an increasing number of novel organisms’ genomes are obtained, and also re-sequencing, such as the 1000 Genomes Project or the Cancer Genome Atlas. Throughout evolution, there exist specific locations in the genome across species which are conserved after speciation events. For instance, the functional gene TIP49 encoding for an enzyme within a nuclear protein complex related to DNA helicase activity is highly conserved due to its fundamental role in biological processes (Mac Farlane 2010). Multiple sequence alignment of different species are used for homology inference and evolutionary relationship analyses with the ultimate goal to have a better understanding of the genetic code. Tools and algorithms have been developed to accurately align sequences based on scoring schemes and DNA prediction models, ensued by estimation of evolution distance and phylogenetic tree reconstruction. However, a caveat to be taken into consideration is that genomic conservation tends to be omitted which might lead to inaccurate results.

## Motivation
Besides the improvement of sequencing tools, research on the genome has been a major field of study throughout the recent decade. From Sanger sequencing to Next-Generation sequencing, the discovery of information encrypted in the sequences of nucleotides provide a better understanding of the genome. Sequencing could involve functional genomics, RNA-seq, ChIP-seq, whole genome sequencing or epigenomics. Different instruments manufactured and designed by various companies rely on different sequencing methods, such as amplification PCR or bridge amplification, to obtain the desired output sequences. ROCHE GXFLS uses pyrosequencing techniques and is appropriate for Amplicon sequencing, while ILLUMINA HISEQ employs sequencing by synthesis and is ideal for high-throughput sequencing. Comparative genomics utilizes multiple sequence alignment tools, including CLUSTAL, TCOFFEE and MUSCLE, in order to infer the phylogenetic relationships between species and assess the function of ubiquitous genetic regions across organisms. Although multiple sequence alignment algorithms yield satisfactory results, they might not fully reflect the evolutionary correlation underlying the genomic structures. With the endeavour to better represent the alignments of different species, the concept of conservation comes into play, as it is in reality a major factor intertwined with speciation events. Distinct regions in the genome, whether coding or regulatory, are exposed to evolutionary forces altering the bases of the DNA. Transitions and transversions occur inevitably through time, but there are locations in the genome more robust to modification, whereas others are prone to transforming. The experiment was conducted by using two different sets of conservation scores, notably PHYLOP and GERP. The resulting multiple sequence alignments produced were analyzed and assessed.

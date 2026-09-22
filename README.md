# Bioinformatics Lab Activity

* **Name:** Ray Gee J. Lisondra
* **Assigned Gene:** LDLR (Low-Density Lipoprotein Receptor)
* **Associated Disease:** Familial Hypercholesterolemia


## Assigned Gene and Disease
* **Official Gene Symbol:** LDLR
* **Full Gene Name:** Low-Density Lipoprotein Receptor
* **Associated Disease:** Familial Hypercholesterolemia (characterized by high levels of low-density lipoproteins and premature cardiovascular disease).


## UCSC Gene Location 
* **Chromosome:** Chromosome 19 (Band 19p13.2)
* **Genome Assembly Used:** GRCh38/hg38
* **Genomic Coordinates in UCSC:** chr19:11,089,463-11,133,820
* **DNA Strand:** Positive strand (+) 
* **Approximate Gene Size / Length:** 44,358 bp 

### Screenshot 1: Gene Location in UCSC
*Description: The UCSC Genome Browser displaying the LDLR gene region on chromosome 19 with visible genomic coordinates and gene symbol.*
* [View screenshot 1 (Gene Location)](screenshots/01_gene_location.png)


## Exons, Introns, and Transcripts 
* **Number of Exons (in selected transcript):** 18 exons
* **Multiple Transcripts/Isoforms:** Yes, multiple alternative transcripts and isoforms are visible stacked horizontally below the main reference tracks.
* **Definition of Exon vs. Intron:** Exons are the segments of the gene that are retained in mature transcripts, whereas introns are the intervening non-coding segments that are spliced out .
* **Intron vs. Exon Length Observation:** The introns generally appear substantially longer than the exons, creating large physical gaps between the relatively compact exon blocks.

### Screenshot 2: Gene Structure and Transcripts
*Description: Detailed view of the LDLR gene structure showing exon boxes, intron connecting lines, and multiple transcript variants.*
* [View screenshot 2 (Gene Structure)](screenshots/02_gene_structure.png)


## Genome Browser Tracks 
* **a. Gene annotation track used:** NCBI RefSeq 
* **b. ClinVar-related variant marks:** Yes, ClinVar variant marks are visible within and surrounding the gene region.
* **c. Conservation variation:** Yes, certain regions exhibit noticeably stronger conservation signals than others across species.
* **d. Conserved region location:** Conserved regions correspond predominantly to coding exons and important functional segments.
* **e. Significance of conservation:** Strong sequence conservation across species implies that the region is under purifying selection. This suggests that the sequence serves a critical biological function and cannot tolerate random mutations without negative consequences.

### Screenshot 3: Browser Tracks (ClinVar SNVs and Conservation)
*Description: UCSC Genome Browser view displaying the LDLR gene alongside active ClinVar SNV density and gene models.*
* [View screenshot 3 (Browser Tracks)](screenshots/03_tracks.png)

## ClinVar Variant Selection 

* **a. Gene:** LDLR
* **b. Variant HGVS / Description:** NM_000527.5(LDLR):c.1A>T (p.Met1Leu)
* **c. rsID or ClinVar Variation ID/VCV accession:** 250968
* **d. Chromosome and genomic position:** 19; 11089549 (GRCh38)
* **e. Associated Condition / Disease:** Hypercholesterolemia, familial 1
* **f. Clinical Significance:** Pathogenic
* **g. Review Status:** Reviewed by expert panel (3-star expert panel submission)
* **h. ClinVar Record URL:** https://www.ncbi.nlm.nih.gov/clinvar/variation/250968/

### Screenshot 4: ClinVar Variant Record
* [View Screenshot 4 (ClinVar Variant)](screenshots/04_clinvar_variant.png)

## Variant Mapping and Functional Context 

* **a. Where is the variant located relative to your gene?** The variant is located at genomic coordinate chr19: 11089549, positioned right at the 5' beginning of the LDLR gene.
* **b. Is it in an exon, intron, UTR, splice region, or another region?** It is located inside an exon (specifically Exon 1 of the transcript models).
* **c. Is it likely in a coding or non-coding region based on the displayed annotations?** Based on the GENCODE and RefSeq annotations, it is in a coding region, specifically affecting the translation initiation codon.
* **d. Based on its location and ClinVar information, briefly explain how the variant might affect the gene or gene product:** Because the variant alters the starting methionine (Met1) codon of the LDLR gene, it likely disrupts normal translation initiation or results in an unstable, non-functional protein. This leads to receptor deficiency, which causes impaired clearance of LDL cholesterol (the pathological mechanism of familial hypercholesterolemia).
* **e. What additional evidence would be needed before concluding that the variant causes disease?** Conclusive proof requires functional assays measuring cellular LDL uptake, family co-segregation analysis, and low population allele frequency data.
  
### Screenshot 5: Variant Position in UCSC
* [View Screenshot 5 (Selected variant)](screenshots/05_variant_in_ucsc.png)

## Reflection Questions

* **1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?**
  The UCSC Genome Browser visually displayed the exact structural organization of the *LDLR* gene on chromosome 19. While functional summaries explain the gene's biological role, the browser mapped its physical exon-intron structure and precise base-pair coordinates.

* **2. Why is knowing the exact genomic location of a disease-associated variant useful?**
  Precise genomic coordinates allow researchers to cross-reference variant databases like ClinVar against assemblies like GRCh38. This  context identifies whether a mutation affects a coding region, UTR, or splice site, guiding downstream analysis.

* **3. What is one limitation of predicting a variant's effect only from its genomic location?**
  Genomic location only provides structural context without confirming the actual functional impact on the gene product. Concluding pathogenicity requires experimental validation, as positional data alone cannot measure cellular phenotype changes.

* **4. What was the most interesting feature you observed about your assigned gene?**
  It was striking to see how a single-nucleotide substitution (c.1A>T) at the start of Exon 1 disrupts the translation initiation codon (p.Met1Leu). This illustrates how a tiny point mutation at a critical locus can drive a severe genetic disorder like Familial Hypercholesterolemia.

## References and Links

* **NCBI ClinVar:** National Center for Biotechnology Information. ClinVar database entry for LDLR variant (c.1A>T) (Variation ID: 250968). Available at: [https://www.ncbi.nlm.nih.gov/clinvar/variation/250968/]
* **UCSC Genome Browser:** Human (GRCh38/hg38) Assembly, UCSC Genomics Institute. LDLR genomic region (chr19:11,089,463-11,133,820). Available at: [https://genome.ucsc.edu/]

#The scripts are derived from https://www.biowolf.cn/.

Instructions

Figure 2 code
geneTMB08.TCGAstat.pl
This script is applied to calculate the somatic mutation characteristics in each sample of the somatic mutation data downloaded from TCGA and cBioportal.

geneTMB09.TCGApreWater.pl
This script is applied to organize the data of somatic mutation characteristics into a format suitable for generating waterfall diagrams.

geneTMB10.GenVisR.R
This script is applied to generate the waterfall plot illustrating frequency of various variant classifications and distribution of different types of variant genes by R package "GenVisR".


Figure 3 code
geneTMB16.venn.R
This script is applied to  intersect the top 30 genes ranked by mutation rate in both groups and generate the venn diagram by R package "Venn".

geneTMB17.TMB.pl
This script is applied to calculate tumor mutation burden values of each sample in TCGA and cBioportal cohort.

geneTMB18.boxplot.R
This script is applied to analyze the correlation between TMB score and gene mutation status  by R package "ggpubr".


Figure 4 code
getClinical.pl
This script is applied to organize the clinical information downloaded from TCGA into a suitable format for further analysis.

geneTMB19.preSurvival.R
This script is applied to combine the mutation data with survival data of patients in TCGA cohort.

geneTMB20.survival.R
This script is applied to perform survival analysis for exploring prognosis-related mutations and generate Kaplan–Meier survival curves by R package "survival" and "survminer".


Figure 5 code
geneTMB21.indep.R
This script is applied to perform univariate and multivariate Cox regressions to idendity independent prognosis-related characteristics.


Figure 6 code
moveFiles.pl&merge.pl
These two scripts are applied to organize the transcriptome data downloaded from TCGA into a suitable format for further analysis.

symbo.pl
This script is applied to convert the ensembl IDs in TCGA transcriptome profile to official gene symbols.

snpRNA10.getSampleExp.pl
This script is applied to divide the patients in TCGA cohort into wild and mutant types depending on gene mutation status.

snpRNA11.edgeR.R
This script is applied to perform differentially expressed genes analysis and generate the volcano plot and heatmap by R package "edgeR" and "pheatmap".


Figure 7 code
snpRNA16.symbol2id.R
This script is applied to convert gene symbols to entrez IDs  for further analysis by R package "org.Hs.eg.db".

snpRNA17.GO.R
This script is applied to perform GO functional annotations and generate the bar plot and bubble plot by R package "clusterProfiler," "enrichplot," and "ggplot2".

snpRNA18.KEGG.R
This script is applied to perform KEGG functional annotations and generate the bar plot and bubble plot by R package "clusterProfiler," "enrichplot," and "ggplot2".


Figure 8 code
snpRNA13.preGSEA.pl
This script is applied to organize the transcriptome profile into two input files for GSEA analysis.

snpRNA15.multiGSEA.R
This script is applied to generate the multigene enrichment plot.


Figure 9 code
bioR02.barplotStat
This script is applied to generate the stacked bar plot demonstrating the top 30 hub genes in the protein-protein interaction network.


Figure 10 code
geneTMB25.CIBERSORT.R
This script is the source code of CIBERSORT algorithm.

geneTMB25.run.R
This script is applied to perform CIBERSORT algorithm to estimate the abundance of immune-infiltrating cells.

geneTMB26.immunePlot.R
This script is applied to explore the relationship of different immune cell components and generate the correlation plot by R package "corrplot".

geneTMB27.vioplot.R
This script is applied to investigate the differences of immune cell distribution between different mutation status by R package "limma" and generate the violin plot by R package "vioplot".

snpRNA12.scatter.R
This script is applied to investigate the correlation between the expression of immune checkpoint genes and different gene mutation status by R package "limma".


Tables1,2 code
This script is applied to perform functional annotations for screened hub subnetworks of the protein-protein interaction network by R package "clusterProfiler".























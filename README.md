# TFM-adenocarcinoma-de-pulmon-KRAS-y-EGFR
# Español
# Análisis integrativo multi-ómico del adenocarcinoma de pulmón impulsado por EGFR y KRAS
## Descripción general del proyecto
#### Este repositorio contiene todo el código, las figuras y los materiales de apoyo utilizados en un Trabajo de Fin de Máster centrado en la caracterización molecular integrativa del adenocarcinoma de pulmón (LUAD), con especial énfasis en los tumores impulsados por mutaciones en EGFR y KRAS. El proyecto combina análisis genómicos, transcriptómicos, proteómicos y de RNA-seq de célula única, así como análisis de supervivencia, para investigar diferencias biológicas, vías funcionales e implicaciones clínicas asociadas a cada subtipo molecular. Se utilizaron conjuntos de datos oncológicos públicos de gran escala, incluidos TCGA y AACR GENIE, para garantizar la robustez, reproducibilidad y relevancia clínica de los resultados.
## Objetivos
#### • Caracterizar el panorama mutacional del LUAD con mutaciones en EGFR y KRAS.
#### • Comparar los patrones de co-mutationes y la heterogeneidad molecular entre subtipos.
#### • Identificar genes diferencialmente expresados y vías biológicas enriquecidas.
#### • Integrar datos de RNA-seq a granel, proteómica RPPA y scRNA-seq.
#### • Evaluar diferencias en la supervivencia global mediante análisis de Kaplan–Meier.
#### •  Proporcionar un flujo de trabajo analítico reproducible y transparente.
## Fuentes de datos
#### • TCGA-LUAD: mutaciones somáticas, RNA-seq a granel, proteómica RPPA, datos clínicos y de supervivencia.
#### • AACR GENIE: cohorte independiente de validación con datos genómicos clínicamente anotados.
#### • GEO (GSE131907): conjunto de datos de RNA-seq de célula única de cáncer de pulmón (datos procesados).
#### No se incluyen datos brutos de acceso controlado. Solo se proporcionan resultados derivados y scripts reproducibles.
## Resumen de la metodología
#### Los análisis se realizaron en R utilizando paquetes de Bioconductor y CRAN, incluidos:
#### • TCGAbiolinks, TCGAmutations – adquisición y preprocesamiento de datos
#### • DESeq2 – análisis de expresión génica diferencial
#### • clusterProfiler – enriquecimiento funcional (GO, KEGG)
#### • survival, survminer – análisis de supervivencia
#### • Seurat – análisis de RNA-seq de célula única
#### • ggplot2 – visualización de datos

## Contenidos
#### • Scripts en R completamente anotados utilizados para reproducir todos los análisis.
#### • Tablas de resultados procesados (DEGs, salidas de enriquecimiento, resúmenes de supervivencia).
#### • Figuras de alta resolución utilizadas en el trabajo.
#### • Documentación que describe los pasos analíticos y los supuestos.
## Reproducibilidad
#### Todos los análisis están diseñados para ser reproducibles utilizando conjuntos de datos disponibles públicamente. 
## Contexto académico
#### Este repositorio respalda un Trabajo de Fin de Máster (TFM) en biología computacional/bioinformática y está destinado a un uso académico y no comercial.
## Contacto
#### Para preguntas o colaboraciones, por favor contacte con el autor a través de GitHub.


# English
# Integrative multi-omic analysis of EGFR- and KRAS-driven lung adenocarcinoma
## Project overview
#### This repository contains all the code, figures and supporting materials used in a Master’s Thesis focused on the integrative molecular characterization of lung adenocarcinoma (LUAD), with special emphasis on tumors driven by EGFR and KRAS mutations. The project combines genomic, transcriptomic, proteomic and single-cell RNA-seq analyses, as well as survival analyses, to investigate biological differences, functional pathways and clinical implications associated with each molecular subtype.
#### Publicly available large-scale cancer datasets, including TCGA and AACR GENIE, were leveraged to ensure robustness, reproducibility and clinical relevance of the results.
## Objectives
#### •	Characterize the mutational landscape of EGFR- and KRAS-mutated LUAD.
#### •	Compare co-mutation patterns and molecular heterogeneity between subtypes.
#### •	Identify differentially expressed genes and enriched biological pathways.
#### •	Integrate bulk RNA-seq, RPPA proteomics and scRNA-seq data.
#### •	Evaluate overall survival differences using Kaplan–Meier analysis.
#### •	Provide a reproducible and transparent analytical workflow.
## Data sources
#### •	TCGA-LUAD: somatic mutations, bulk RNA-seq, RPPA proteomics, clinical and survival data.
#### •	AACR GENIE: independent validation cohort with clinically annotated genomic data.
#### •	GEO (GSE131907): single-cell RNA-seq lung cancer dataset (processed data).
#### Raw controlled-access data are not included. Only derived results and reproducible scripts are provided.
## Methodology summary
#### Analyses were performed in R using Bioconductor and CRAN packages, including:
#### •	TCGAbiolinks, TCGAmutations – data acquisition and preprocessing
#### •	DESeq2 – differential gene expression analysis
#### •	clusterProfiler – functional enrichment (GO, KEGG)
#### •	survival, survminer – survival analyses
#### •	Seurat – single-cell RNA-seq analysis
#### •	ggplot2 – data visualization

## Contents
#### •	Fully annotated R scripts used to reproduce all analyses.
#### •	Processed result tables (DEGs, enrichment outputs, survival summaries).
#### •	High-resolution figures used in the thesis.
#### •	Documentation describing analytical steps and assumptions.
## Reproducibility
#### All analyses are designed to be reproducible using publicly available datasets. 
## Academic context
#### This repository supports a Master’s Thesis (TFM) in computational biology/bioinformatics and is intended for academic, non-commercial use.
## Contact
#### For questions or collaborations, please contact the author via GitHub.



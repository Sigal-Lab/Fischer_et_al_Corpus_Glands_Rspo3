# Fischer_et_al_Corpus_Glands_Rspo3
R scripts used for data analysis in Fischer et al. 

Data files required for analysis are provided in Data folder and referenced from R scripts in Code/...

Fig. 6f-i, 7a, 7b, Suppl. Fig. 2h, Suppl. Fig. 9c-e and 11 a-b:

  - Make sure to download any auxiliary data files in Data/External/Yui_et_al_CSC_2018/Colitis_vs_control and Data/External/GeneSets/MSigDB_v7.1 . See respective SOURCE files for details. 
  - Microarray data was preprocessed according to scripts ./Code/Array1/Preprocess_raw_files.Rmd and ./Code/Array2/Preprocess_raw_files.Rmd
  - Differential gene expression was calculated according to scripts ./Code/Array1/ExpressionAnalysis.Rmd and ./Code/Array2/ExpressionAnalysis.Rmd
  - GSEA was run on DGE results using script ./Code/GSEA_2/GSEA_Analaysis.Rmd and GSEA plots were generated using ./Code/GSEA_2/GSEA_plots.Rmd
  - Figure PDFs are in Results/GSEA


Include all the codes for bioinformatics analysis in **Lung-marginated neutrophils regulate capillary blood flow to safeguard blood oxygenation and endothelial fitness.**

# Session info
R version 4.3.3 (2024-02-29)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 24.04.2 LTS

Matrix products: default
BLAS: /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3
LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.26.so; LAPACK version 3.12.0

## locale:
[1] LC_CTYPE=en_US.UTF-8 LC_NUMERIC=C
[3] LC_TIME=fr_BE.UTF-8 LC_COLLATE=en_US.UTF-8
[5] LC_MONETARY=fr_BE.UTF-8 LC_MESSAGES=en_US.UTF-8
[7] LC_PAPER=fr_BE.UTF-8 LC_NAME=C
[9] LC_ADDRESS=C LC_TELEPHONE=C
[11] LC_MEASUREMENT=fr_BE.UTF-8 LC_IDENTIFICATION=C

time zone: Europe/Brussels
tzcode source: system (glibc)

## attached base packages:
[1] grid stats graphics grDevices utils datasets methods
[8] base

## other attached packages:
[1] ComplexHeatmap_2.16.0 dittoSeq_1.12.0 formatR_1.14
[4] ggplot2_3.4.2 patchwork_1.1.2 SeuratObject_4.1.3
[7] Seurat_4.3.0 dplyr_1.1.2

loaded via a namespace (and not attached):
[1] RColorBrewer_1.1-3 shape_1.4.6
[3] rstudioapi_0.14 jsonlite_1.8.7
[5] magrittr_2.0.3 magick_2.7.5
[7] spatstat.utils_3.0-3 farver_2.1.1
[9] rmarkdown_2.23 GlobalOptions_0.1.2
[11] zlibbioc_1.46.0 vctrs_0.6.3
[13] ROCR_1.0-11 Cairo_1.6-2
[15] spatstat.explore_3.2-1 RCurl_1.98-1.12
[17] S4Arrays_1.2.1 htmltools_0.5.5
[19] sctransform_0.3.5 parallelly_1.36.0
[21] KernSmooth_2.23-22 htmlwidgets_1.6.2
[23] ica_1.0-3 plyr_1.8.8
[25] plotly_4.10.2 zoo_1.8-12
[27] igraph_1.5.0.1 iterators_1.0.14
[29] mime_0.12 lifecycle_1.0.3
[31] pkgconfig_2.0.3 Matrix_1.6-1
[33] R6_2.5.1 fastmap_1.1.1
[35] clue_0.3-64 GenomeInfoDbData_1.2.10
[37] MatrixGenerics_1.12.2 fitdistrplus_1.1-11

[39] future_1.33.0 shiny_1.7.4.1
[41] digest_0.6.33 colorspace_2.1-0
[43] S4Vectors_0.38.1 tensor_1.5
[45] irlba_2.3.5.1 GenomicRanges_1.52.0
[47] labeling_0.4.2 progressr_0.13.0
[49] fansi_1.0.4 spatstat.sparse_3.0-2
[51] httr_1.4.6 polyclip_1.10-4
[53] abind_1.4-5 compiler_4.3.3
[55] doParallel_1.0.17 withr_2.5.0
[57] highr_0.10 MASS_7.3-60.0.1
[59] DelayedArray_0.26.3 rjson_0.2.21
[61] tools_4.3.3 lmtest_0.9-40
[63] httpuv_1.6.11 future.apply_1.11.0
[65] goftest_1.2-3 glue_1.6.2
[67] nlme_3.1-164 promises_1.2.0.1
[69] Rtsne_0.16 cluster_2.1.6
[71] reshape2_1.4.4 generics_0.1.3
[73] gtable_0.3.3 spatstat.data_3.0-1
[75] tidyr_1.3.0 data.table_1.14.8
[77] XVector_0.40.0 sp_2.2-0
[79] utf8_1.2.3 BiocGenerics_0.46.0
[81] spatstat.geom_3.2-4 RcppAnnoy_0.0.21
[83] foreach_1.5.2 ggrepel_0.9.3
[85] RANN_2.6.1 pillar_1.9.0
[87] stringr_1.5.0 limma_3.56.2
[89] spam_2.9-1 later_1.3.1
[91] circlize_0.4.15 splines_4.3.3
[93] lattice_0.22-5 survival_3.5-8
[95] deldir_1.0-9 tidyselect_1.2.0
[97] SingleCellExperiment_1.22.0 miniUI_0.1.1.1
[99] pbapply_1.7-2 knitr_1.43
[101] gridExtra_2.3 IRanges_2.34.0
[103] SummarizedExperiment_1.30.2 scattermore_1.2
[105] stats4_4.3.3 xfun_0.39
[107] Biobase_2.60.0 matrixStats_1.0.0
[109] pheatmap_1.0.12 stringi_1.8.4
[111] lazyeval_0.2.2 yaml_2.3.7
[113] evaluate_0.21 codetools_0.2-19
[115] tibble_3.2.1 cli_3.6.1
[117] uwot_0.1.16 xtable_1.8-4
[119] reticulate_1.30 munsell_0.5.0
[121] Rcpp_1.0.11 GenomeInfoDb_1.36.0
[123] globals_0.16.2 spatstat.random_3.1-5
[125] png_0.1-8 parallel_4.3.3
[127] ellipsis_0.3.2 dotCall64_1.0-2
[129] bitops_1.0-7 listenv_0.9.0
[131] viridisLite_0.4.2 scales_1.2.1
[133] ggridges_0.5.4 crayon_1.5.2
[135] leiden_0.4.3 purrr_1.0.1
[137] GetoptLong_1.0.5 rlang_1.1.1
[139] cowplot_1.1.1

# Pull image from BCB420 base image
FROM risserlin/bcb420-base-image:winter2023

# Add DESeq2
RUN R -e "BiocManager::install('DESeq2')"

# Add pheatmap
RUN install2.r \
    -d TRUE \
    -r 'https://cran.rstudio.com' \
    pheatmap

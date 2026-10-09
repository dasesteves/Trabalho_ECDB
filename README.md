# Exploração de dados biológicos

Trabalho de grupo sobre exploração de dados de expressão génica e visualização em R, realizado na unidade curricular de Extração de Conhecimento de Dados Biológicos.

## Materiais do trabalho

- [Código de análise em R](Code_PRAD.R).
- [Relatório — fonte R Markdown](Relat%C3%B3rio.rmd).
- [Código de PCA](PCA%20codigo).

O relatório disponível é o ficheiro-fonte `.rmd`; não existe uma versão PDF ou HTML neste repositório. A sua geração exige o ambiente e os dados usados na análise.

Trabalho académico de grupo de 2023/2024. As fontes e os dados descritos abaixo
documentam esse contexto; este repositório não constitui uma aplicação clínica.

## Reproduzir a análise

O [script principal](Code_PRAD.R) consulta o GDC para o projeto `TCGA-PRAD`,
descarrega os dados e usa `TCGAbiolinks`, `SummarizedExperiment` e `DESeq2`.
Inclui comandos de instalação de pacotes; executar o ficheiro completo também
executa essas etapas e a recolha de dados.

As versões de R e dos pacotes não estão fixadas num ficheiro de ambiente.
Antes de repetir o trabalho, rever a consulta e os caminhos do script e guardar
as versões usadas com `sessionInfo()`. A ligação ao cBioPortal abaixo mantém
a referência ao conjunto de dados indicado no trabalho; a recolha do script
é definida pela consulta ao GDC. Os resultados históricos não foram reexecutados
para esta revisão da documentação.

## Elementos do Grupo 6:  

- PG 52170 - Armindo
- PG 54434 - Afonso
- PG 28935 - Diogo Esteves

## Objetivo:
O trabalho tem como objetivo a análise do conjunto de dados obtidos a partir do cBioPortal, utilizando Python e software como o R com pacotes incorporados e outros disponíveis como o Bioconductor.

## Dados selecionados:
[Prostate Adenocarcinoma (TCGA, PanCancer Atlas)](https://www.cbioportal.org/study/summary?id=prad_tcga_pan_can_atlas_2018)

**GDC Identifiers:**

*Case UUID :*   
a608bf0e-a932-4541-8439-2ffb9f6294b0  
*Case ID :*   
TCGA-EJ-A46E  
*Project :*   
TCGA-PRAD  
*Project Name :*   
Prostate Adenocarcinoma  
*Disease Type :*   
Adenomas and Adenocarcinomas  
*Program :*   
TCGA  
*Primary Site :*   
Prostate gland

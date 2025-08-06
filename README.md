
# MSI Clustering Suite

Questa è un'applicazione **Shiny** per l'analisi e il clustering di dati di **spettrometria di massa da immagini (MSI)**.

L'app permette di:
- caricare dati in formato `.rds` o `.imzML`
- scegliere tra diverse metriche di distanza e algoritmi di clustering
- visualizzare e classificare nuovi tessuti
- salvare i risultati come report `.csv`

## 📁 Struttura della cartella


## 🚀 Come eseguire l'app

Assicurati di avere R e le seguenti librerie installate:

```r
library(shiny)
library(ggplot2)
library(viridis)
library(dplyr)
library(proxy)
library(readxl)
library(vegan)
library(plotly)
library(data.table)
library(tools)
library(bslib)
library(gridExtra)
library(Cardinal)
library(SummarizedExperiment)
library(MALDIquant)
library(MALDIquantForeign)

shiny::runApp("lancio_app.R")

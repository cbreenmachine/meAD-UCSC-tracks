# README.md

This repo contains data for UCSC upload.  Copy the snippets below and change the file name.

`track type=bigLolly name="-log10(lFDR)" description="Hyper (blue), hypo (yellow), and non-significant (grey) CpGs" bigDataUrl=https://raw.githubusercontent.com/cbreenmachine/UCSC-data/main/DMPs.lolly.bb lollySizeField=lollySize visibility=full`

and 

`track type=bigInteract name="Promoter-Enhancer Interactions" description="Interactions from PCHi-C" useScore=on bigDataUrl=https://raw.githubusercontent.com/cbreenmachine/UCSC-data/main/interactions.bb visibility=full`  


## Version for paper (April 27, 2023)
```
track type=bigLolly name="DMPs" bigDataUrl=https://raw.githubusercontent.com/cbreenmachine/UCSC-data/main/DMPs-lolly.hg38.bb lollySizeField=lollySize visibility=full

track type=bigInteract name="Promoter-Enhancer Interactions" useScore=on bigDataUrl=https://raw.githubusercontent.com/cbreenmachine/UCSC-data/main/interactions-with-DMP.hg38.bb visibility=full
```

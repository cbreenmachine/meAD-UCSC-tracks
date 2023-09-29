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

## Copy and Paste for Interactions B4GALT1
```
track type=interact name="Promoter-Enhancer Interactions" useScore=on visibility=full
#chrom	chromStart	chromEnd	name	score	value	exp	color	sourceChrom	sourceStart	sourceEnd	sourceName	sourceStrand	targetChrom	targetStart	targetEnd	targetName	targetStrand
chr9	32451004	32460518	.	500	5	.	255,0,0	chr9	32519385	32524065	OtherEnd:enhancer	.	chr9	32382623	32396972	Bait:promoter	.
chr9	32770879	32775142	.	500	5	.	255,0,0	chr9	32519385	32524065	OtherEnd:enhancer	.	chr9	33022373	33026220	Bait:promoter	.
chr9	33106073	33114268	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33163023	33172125	Bait:promoter	.
chr9	33106073	33114268	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33163023	33172125	Bait:promoter	.
chr9	33106073	33114268	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33163023	33172125	Bait:promoter	.
chr9	33110625	33116865	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33172126	33177320	Bait:promoter	.
chr9	33110625	33116865	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33172126	33177320	Bait:promoter	.
chr9	33110625	33116865	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33172126	33177320	Bait:promoter	.
chr9	33129783	33137910	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33210443	33219410	Bait:promoter	.
chr9	33129783	33137910	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33210443	33219410	Bait:promoter	.
chr9	33129783	33137910	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33210443	33219410	Bait:promoter	.
chr9	33130513	33140669	.	500	5	.	255,0,0	chr9	33098004	33109213	OtherEnd:enhancer	.	chr9	33163023	33172125	Bait:promoter	.
chr9	33135065	33143266	.	500	5	.	255,0,0	chr9	33098004	33109213	OtherEnd:enhancer	.	chr9	33172126	33177320	Bait:promoter	.
chr9	33149146	33165143	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33249168	33273876	Bait:promoter	.
chr9	33149146	33165143	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33249168	33273876	Bait:promoter	.
chr9	33149146	33165143	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33249168	33273876	Bait:promoter	.
chr9	33154223	33164311	.	500	5	.	255,0,0	chr9	33098004	33109213	OtherEnd:enhancer	.	chr9	33210443	33219410	Bait:promoter	.
chr9	33158485	33164188	.	500	5	.	255,0,0	chr9	33241342	33249167	OtherEnd:enhancer	.	chr9	33075629	33079209	Bait:promoter	.
chr9	33168043	33174711	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33286962	33293011	Bait:promoter	.
chr9	33168043	33174711	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33286962	33293011	Bait:promoter	.
chr9	33168043	33174711	.	500	5	.	255,0,0	chr9	33049124	33056411	OtherEnd:enhancer	.	chr9	33286962	33293011	Bait:promoter	.
chr9	33423325	33432123	.	500	5	.	255,0,0	chr9	33374151	33388703	OtherEnd:enhancer	.	chr9	33472499	33475543	Bait:promoter	.
```

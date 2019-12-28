# DisGeNET

* ID - disgenet
* Description - Musicians and their groups
* Data Source - [DisGeNET](http://www.disgenet.org/)
* License - CC BY-NC-SA 4.0
* Size (.pg) - 120 MB
* Node Count - 41,860
* Edge Count - 628,685

## Sample

### Nodes - Disease

```
"http://linkedlifedata.com/resource/umls/id/C0000731"	:Disease	name:"Abdomen distended [umls:C0000731]"
"http://linkedlifedata.com/resource/umls/id/C0000735"	:Disease	name:"Abdominal Neoplasms [umls:C0000735]"
"http://linkedlifedata.com/resource/umls/id/C0000737"	:Disease	name:"Abdominal Pain [umls:C0000737]"
```

### Nodes - Gene

```
"http://identifiers.org/ncbigene/1"	:Gene	name:"alpha-1-B glycoprotein [ncbigene:1]"	symbol:"A1BG [hgnc:A1BG]"	specifisity:0.857	pleiotropy:0.172	protein:"P04217 [uniprot:P04217]"
"http://identifiers.org/ncbigene/10"	:Gene	name:"N-acetyltransferase 2 [ncbigene:10]"	symbol:"NAT2 [hgnc:NAT2]"	specifisity:0.466	pleiotropy:0.828	protein:"P11245 [uniprot:P11245]"
"http://identifiers.org/ncbigene/100"	:Gene	name:"adenosine deaminase [ncbigene:100]"	symbol:"ADA [hgnc:ADA]"	specifisity:0.494	pleiotropy:0.793	protein:"P00813 [uniprot:P00813]"
```

### Edges - hasAssociatedGene

```
"http://linkedlifedata.com/resource/umls/id/C0000731"	->	"http://identifiers.org/ncbigene/10653"	:hasAssociatedGene	score:0.1
"http://linkedlifedata.com/resource/umls/id/C0000731"	->	"http://identifiers.org/ncbigene/11231"	:hasAssociatedGene	score:0.1
"http://linkedlifedata.com/resource/umls/id/C0000731"	->	"http://identifiers.org/ncbigene/1280"	:hasAssociatedGene	score:0.1
```

### Edges - hasAssociatedGene

```
"http://linkedlifedata.com/resource/umls/id/C0000737"	->	"http://identifiers.org/dbsnp/rs1057518806"	:hasAssociatedVariant	score:0.7
"http://linkedlifedata.com/resource/umls/id/C0000737"	->	"http://identifiers.org/dbsnp/rs1057518886"	:hasAssociatedVariant	year:2015	score:0.7
"http://linkedlifedata.com/resource/umls/id/C0000744"	->	"http://identifiers.org/dbsnp/rs146064714"	:hasAssociatedVariant	year:1995	year:1996	year:2000	year:2007	score:0.7
```

## How Generated

    $ g2g disgenet.g2g http://rdf.disgenet.org/sparql/

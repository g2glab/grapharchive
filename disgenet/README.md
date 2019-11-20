# DisGeNET

* ID - disgenet
* Description - Musicians and their groups
* Data Source - [DisGeNET](http://www.disgenet.org/)
* License - 
* Size - KB
* Node Count -
* Edge Count -

## Sample

### Nodes - Disease

```
"http://linkedlifedata.com/resource/umls/id/C0000731"   :Disease
"http://linkedlifedata.com/resource/umls/id/C0000735"   :Disease
"http://linkedlifedata.com/resource/umls/id/C0000737"   :Disease
```

### Nodes - Gene

```
"http://identifiers.org/ncbigene/1"     :Gene
"http://identifiers.org/ncbigene/10"    :Gene
"http://identifiers.org/ncbigene/100"   :Gene
```


### Edges - same_group

```
"http://linkedlifedata.com/resource/umls/id/C0000731"   ->      "http://identifiers.org/ncbigene/10653" :associates     score:0.1
"http://linkedlifedata.com/resource/umls/id/C0000731"   ->      "http://identifiers.org/ncbigene/11231" :associates     score:0.1
"http://linkedlifedata.com/resource/umls/id/C0000731"   ->      "http://identifiers.org/ncbigene/1280"  :associates     score:0.1
```

## How Generated

    $ g2g mapping.g2g http://rdf.disgenet.org/sparql/

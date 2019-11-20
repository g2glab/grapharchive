# Wikidata disease-related data

* ID - wikidata_disease
* Description - Wikidata disease-related data
* Data Source - [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page)
* License - CC0
* Size - 1.9MB
* Node Count - 10488
* Edge Count - 11770

## Sampled lines

### Nodes - diseases
```
"http://www.wikidata.org/entity/Q3589156"       :Disease        name:"Malignant Migrating Partial Seizures in Infancy"
"http://www.wikidata.org/entity/Q3589157"       :Disease        name:"Autosomal dominant nocturnal frontal lobe epilepsy"
"http://www.wikidata.org/entity/Q3589131"       :Disease        name:"epidermolysis bullosa dystrophica"
```

### Nodes - human genes
```
"http://www.wikidata.org/entity/Q14860336"      :HumanGene      symbol:NSF
"http://www.wikidata.org/entity/Q18031866"      :HumanGene      symbol:TBX3
"http://www.wikidata.org/entity/Q18031853"      :HumanGene      symbol:TBX5
```

### Nodes - drugs
```
"http://www.wikidata.org/entity/Q7860340"       :Drug   name:Tyloxapol
"http://www.wikidata.org/entity/Q7842225"       :Drug   name:trimetrexate
"http://www.wikidata.org/entity/Q424760"        :Drug   name:dutasteride
```

### Edges - has genetic association
```
"http://www.wikidata.org/entity/Q184674"        ->      "http://www.wikidata.org/entity/Q5008444"       :hasAssociation
"http://www.wikidata.org/entity/Q184674"        ->      "http://www.wikidata.org/entity/Q18042985"      :hasAssociation
"http://www.wikidata.org/entity/Q184674"        ->      "http://www.wikidata.org/entity/Q18040616"      :hasAssociation
```

### Edges - has drug
```
"http://www.wikidata.org/entity/Q183130"        ->      "http://www.wikidata.org/entity/Q286846"        :hasDrug
"http://www.wikidata.org/entity/Q183130"        ->      "http://www.wikidata.org/entity/Q254296"        :hasDrug
"http://www.wikidata.org/entity/Q1827605"       ->      "http://www.wikidata.org/entity/Q670131"        :hasDrug
```

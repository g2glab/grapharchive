# Musician Network from DBPedia

* ID - dbpedia_musician
* Description - Musicians and their groups
* Data Source - DBPedia
* License - CC BY-SA 3.0
* Size - 292 KB
* Node Count - 554
* Edge Count - 1530

## Sample

### Nodes (Musician)

```
"http://dbpedia.org/resource/4th_Disciple"	:Musician	vis_label:"4th Disciple"	hometown:"New York (state)"	hometown:"Steubenville, Ohio"	hometown:"Staten Island"
"http://dbpedia.org/resource/A._R._Rahman"	:Musician	vis_label:"A. R. Rahman"
"http://dbpedia.org/resource/Aaron_Cometbus"	:Musician	vis_label:"Aaron Cometbus"	hometown:"Berkeley, California"
```

## How Generated

    $ wget https://raw.githubusercontent.com/g2glab/g2g/master/examples/musician/musician.g2g
    $ g2g musician.g2g http://dbpedia.org/sparql

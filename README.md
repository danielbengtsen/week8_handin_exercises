# Week8_handin_exercises
## Opgave lavet af:
- Emil Grønlund (cph-eg60@cphbusiness.dk).
- Jimmy Pham (cph-jp327@cphbusiness.dk).
- Jannich Højmose (cph-jm312@cphbusiness.dk).
- Daniel A. Bengtsen (cph-db145@cphbusiness.dk).

### Opgave 1:
- Brug Python til at lave en database ved navn "cars" med tabellen; "the_cars" og kolonerne; "id", "make", "model", "year", "gas_pr_km". Indsæt data i tabellen ud fra en csv-fil med følgende indhold:<br />
1,Volvo,RX2,2011,17<br />
2,Mazda,Ty4,2015,16<br />
3,Toyota,Aygo,2017,20<br />
4,BMW,KL-1,2012,14<br />

### Opgave 2:
- Lav et GET-endpoint "/cars/{id}" som viser en bil med det givne ID.

### Opgave 3:
- Lav et POST-endpoint "cars/add" som tilføjer en ny bil til database ved følgende JSON-format:<br />
{<br />
&nbsp;&nbsp;"make": "MAKE_HERE",<br />
&nbsp;&nbsp;"model": "MODEL_HERE",<br />
&nbsp;&nbsp;"year": XXXX,<br />
&nbsp;&nbsp;"gas_pr_km": "GAS_HERE"<br />
}<br />

### Opgave 4:
- Lav et bar chart der har bil mærke og model på x-aksen (f.eks. "Volvo RX2") og brandstof pr. km på y-aksen (f.eks. 17).

### Ekstra opgave:
- Lav et DELETE-endpoint "cars/{id}" som fjerner bilen fra databasen med det pågældende id.

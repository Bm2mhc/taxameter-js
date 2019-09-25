# Taxameter.js
## En opgave i Strategy Pattern

### Opgave 1
Jeg lavede en pris beregner i selve taxameter.js filen. 

### Opgave 2
Jeg kopirede krone-taxa.html og krone-taxa.js og ændrede der hvor der stod kronetaxa til kronetaxastor. Så lavede jeg et pricestrategy i kronetaxa.js og kronetaxastor.js. Den blev så taget og brugt i taxameteret til at sende prise vidre til start.js


### Opgave 3
Jeg kopirede krone-taxa.html og krone-taxa.js og lavede dem om til citybilen. Derefter ændrede jeg pristrategeyen i js filen til at starte med en variable som samlede pristrategeyen fra før med de nye priser til en variable som hed price. så lavede jeg et if statment:

if (price < 75){

return 75;
} else {
return price
}

Så hvis price er under 75 vil den altid return 75

### Opgave 4
Ændrede pricestategeyen i kronetaxa til at hver del af betalingen blev en variable

Var price = ((afstand-1)*9)
Var priceunder1 = (5*math.min(1, afstand))
var tid = (tidgaaet*(pris for tid))

return price + priceunder1 + tid


### Bonus opgave 1 (overkommelig)
Udvid Taxameter.js med et firmanavn og en tekstbeskrivelse af prismodellen. Dette kræver at start.js bliver ændret en smule.


### Bonus opgave 2 (svær)
Elin Rejser har fået adgang til alle prismodellerne, og deres prismodel er altid den billigste af de andre modeller.

Lav filerne elin-rejser.js og elin-rejser.html og genbrug så meget som mulig kode fra de andre systemer uden at have duplikeret kode.

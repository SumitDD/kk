# Opgaver til uge 45 
## Rækkefølgen 
### world-databasen med spørgsmål
- download databasen herfra og indlæs i din locale database (hvis du ikke allerede har den liggende)
- løs opgaverne

### shop-databasen med spørgsmål
- download databasen og indlæs i din egen database
- brug show create table <tablename> til at få et overblik
- brug workbench' reverse-engineering-værktøj til at få et diagram over databasen
- løs opgaverne

### simpleDog-projektet - fyld en database med test-data
- projektet ligger i branchen dogs
- clon projektet og åben det i netbeans. Projektet består af to klasser - Dog og ImportDogsFromFile - og en testklasse. Fidusen er at testklassen kan bruges til at køre en metode uden at man skal kalde main.
- Tjek folderen Data som ligger øverst i projektet. Der ligger en fil - dogsOffspringtest2.csv. 
Første opgave består i at læse filen med metoden importDogsFromCSV og ud fra hver linje i filen skal man lave en valid insert-statement.
Det vil sige at man skal bygge en sql-streng som man kan printe til konsollen eller endnu bedre skrive til en fil.
Man kan så tage filen direkte og importere vha WorkBench.
For at det virker skal man lave en database. Dernæst skal man lave en hundetabel - kald den dogs - som svarer til hunde-klassen Dog.java. 
Og "svarer til" vil sige at man skal oversætte hundeklassens attributter til søjler i tabellen. 
I denne del af opgaven skal man ignorere de to felter om motherid og fatherid. Så importér hunde uden data om offspring.
Når det virker for test-filen kan man importere den store fil - playforddogsOffSpring.csv -som rummer 16653 rækker

- Næste opgave går ud på at man manuelt indsætter en mor og en far for en vist antal hunde.
(linjen 26898,Blenheim,Spaniel,SAMO,Male,HILLIER,26901,26899 er et eksempel på en linje som skal indsættes)
- Sidste opgave består nu i at lave en select hvor man joiner tabellen med sig selv så man kan se hunde og deres mødre.


### 1
https://www.w3schools.com/sql/exercise.asp Vid första tillfället kan du hoppa över join, group by och database.

### 2
https://sqlbolt.com/lesson/select_queries_introduction Vid första tillfället kan du göra 1 - 4 och 13 - 16.


### 3

Skriv en query som returnerar...

1. All information från tabellen `employees`
2. Förnamn, efternamn, telefonnummer och adress från `employees`
3. Förnamn, efternamn och på alla employees som blev anställda 1993 eller senare.
4. Förnamn och efternamn på alla anställda med
   employees som har managern Steven Buchanan
5. Förnamn och efternamn på alla anställda som inte lagt in sitt telefonnummer i databasen
6. Förnamn och efternamn på alla anställda vars efternamn börjar på D
7. Förnamn och efternamn på alla managers.

### 4

Använd domänen från rollspelsövningen från förra lektionen.

Skriv nu följande queries av olika svårighetsgrad:

- Lista hela inventory för spelaren ”kristian”.
- Hitta det genomsnittliga värdet för alla föremål i spelet.
- Hitta för varje föremål antalet spelare som bär det i sitt _inventory_. Resultatet bör innehålla två kolumner, en för föremåls-ID och en för antal spelare. Se till att visa 0 för föremål som ingen har i sitt _inventory_.
- Hitta för varje spelare namnet på nuvarande weapon eller strängen "Inget" om spelaren inte har något weapon. Resultatet bör ha kolumner för spelarnamn och föremålsnamn.
- Hitta namnet på alla föremål med ett värde av minst 500 och som är utrustade av minst en spelare med en level över 75.
- Hitta för varje spelare det totala kombinerade värdet av alla föremål de har på sig och som de har i sitt _inventory_. Resultatet bör ha två kolumner, en för spelarnamn och en annan för totalt värde. Spelare som inte har några föremål behöver inte finnas med i resultatet.
- Hitta alla föremål i Roberts inventory som han kan ta på sig direkt. Det innebär att föremålet måste gå att ta på sig i en av Roberts lediga slots. En hjälm ska alltså inte finnas med i resultatet om Robert redan bär på en hjälm. Resultatet bör ha två kolumner, id och equipslot

### 5
TBA


### 6

https://leetcode.com/problems/find-total-time-spent-by-each-employee/

### 7

https://leetcode.com/problems/number-of-unique-subjects-taught-by-each-teacher/


### 8

USAs röstningssystem bygger på att varje delstat har ett visst antal elektorer, och kandidaten som har flest röster i delstaten får alla rösterna från elektorerna. Den med flest röster från elektorer vinner sedan valet. Kolla upp detta på internet om du är lite osäker inför uppgiften.

1. Skapa en tabell

```
state_votes(_state_code_, biden_votes, trump_votes, electors)
```

och sätt in lite fiktiv data.

2. Skapa en view `state_results` med en kolumn med statens kod, en med den vinnande presidentkandidaten, och en sista med antalet elektorer som kandidaten har vunnit. Tips: kolla in `CASE`.

3. Skriv en query som slutligen visar hur många totala röster varje kandidat har fått.

4. Byt nu tabellen till:

```
state_votes(_state_code_, _candidate_, votes, electors)
```

Gör om uppgift 2 och 3 med den nya tabellen. Tips: kolla in `RANK()` och andra window-functions.

Vilken struktur är bäst anser du? Finns det några för och nackdelar?


### 9
https://leetcode.com/problems/bank-account-summary-ii/

### 10
https://leetcode.com/problems/last-person-to-fit-in-the-bus/description/


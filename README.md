# Undervisningsmaterial och övningar för Programmering 1

Här kommer jag samla undervisningsmaterial och övningar för kursen. Materialet kommer finnas tillgängligt parallellt med materialet i Classroom. Det är huvudsakligen tänkt som en extra resurs för undervisningen. Allt material kommer att länkas från Classroom så att man enkelt hittar hit.
&nbsp;  

# Vecka 36

TODO: Sammanfattning av veckans undervisning
&nbsp;  

# Vecka 37

Övningar på input, output, variabler, datatyper, if-satser:

  1. Öppna terminalen (cmd) och starta sedan programmet irb (Interactive Ruby Shell) som tillåter oss att testa små kodsnuttar. Titta i cheat-sheet på jämförelse-operatorer. Se även till att du har koll på datatyperna string och integer (text och heltal). Testa några olika jämförelser, t ex: `3 > 4`, `5 == 5`, `"1337" == 1337`, `"hello" == "Hello"`, `"Hello" == "Hello"`. Vad får du för resultat? Varför måste vi ha kolla på datatyper när vi programmerar?
  
  2. Öppna VS Code och lägg till en ny Ruby-fil som heter `firstlastname.rb`. Se till att filen hamnar i rätt workspace (dvs i din Ruby-mapp i din hemkatalog). Studera koden för programmet `name.rb` som vi skrev tidigare. Utöka nu koden så att den efterfrågar förnamn och sedan efternamn från användaren. Tänk på att lagra förnamn och efternamn i två olika variabler. Kalla variablerna `firstname` respektive `lastname`. Programmet ska till sist skriva ut en hälsningsfras i stil med `Hej på dig Gunnar Svensson!`. Titta i cheat-sheet på sträng-interpolering om du är osäker på hur du ska få variablerna på rätt plats i hälsningsfrasen.
  
  3. Skapa ett program som heter `sum.rb`. I koden ska du tilldela integer-värdet 3 till variabeln `num1` och integer-värdet 4 till variabeln `num2`. Vilken output genererar programmet vid körning om du lägger till följande kodrad? :
  `puts "Summan av #{num1} och #{num2} är #{num1 + num2}"`

  4. Skriv ett program `password.rb` som efterfrågar användarnamn (variabeln `username`) och lösenord (variabeln `password`) via `gets.chomp`. Skriv därefter en if-sats i koden som kontrollerar om användarnamnet respektive lösenordet är korrekt. Du kan använda valfria sträng-värden för det rätta användarnamnet och lösenordet. Tänk på att börja if-satsen med kontroll av användarnamnet. Därefter kan if-satsen kontrollera lösenordet. Om något av värden inte stämmer ska programmet skriva ut ett felmeddelande. Om varken användarnamn eller lösenord stämmer ska programmet också skriva ett lämpligt felmeddelande.

  5. Skriv ett program `greatest_of_two.rb` som efterfrågar två heltal (integer-värden). Använd t ex `num1 = gets.to_i` och `num2 = gets.to_i` för att mata in talen i variablerna `num1` respektive `num2`. Använd därefter en if-sats för att skriva ut vilket tal som är störst.
&nbsp;  


# Vecka 41

Extra uppgifter för er som inte har något att göra.

  1. Skriv om kalkylatorn från uppgift 0 så att den hanterar tre operander och två operatorer.

  2. Skriv ett program som simulerar tärningskast med en sex-sidig tärning. Programmet ska efterfråga
antal kast från användaren och därefter genomföra så många kast som användaren angav.
Programmet ska endast skriva ut hur många gånger som vardera sida av tärningen visades. Använd följande syntax för att generera slumptal i intervallet 1-6:
rand(6) + 1

  3. Implementera kortspelet 21! Målet med spelet är att nå summan 21 genom att summera slumpvisa
kort från en kortlek. Spelet fortsätter så länge summan av dina kort är lägre än 21. Om du når
summan 21 har du vunnit och spelet avslutas. Om summan blir högre än 21 har du förlorat och
spelet avslutas. Om du drar ett ess får detta räknas som 1 eller 14 (användaren uppmanas då välja
värde).



# Lösning

![Korrigerad källkod](bilder/fiveErrorsCorrected.png)

Figur 3.

1. Det reserverade ordet static skrivs inte ´´´Static´´´ utan ´´´static´´´.
2. Variabeln ´´´weeklyWages´´´ är inte korrekt deklarerad – typen saknas. Lämplig typ att använda är ´´´double´´´ då resultatet av den aritmetiska operationen * är ett ´´´double´´´. Prova gärna att deklarera ´´´weeklyWages´´´ som ´´´int´´´ och se vad som händer.
3. Strängar som ska skrivas ut måste omslutas av citattecken ("). I detta fall saknades det avslutande.
4. Ett semikolon saknas. Alla satser måste avslutas med ett semikolon.
5. Klammerparenteser förekommer alltid i par. Här saknades den avslutande klammerparentesen (}).
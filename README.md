# Int-Elligence-5-
Innlevering til IS-105
1. Programmer i go utføres med kommandoet go run <filnavn> Da genereres det ingen objektfil (en fil som man kan utføre på en platform , og hvis format er platformavhenging). Hvis man ønsker å generere 1 en objektfil, er kommandoet go build <filnavn>. Finn ut hva  objektfiler heter for de mest brukte platformene (Unix/Linux, MS Windows, Mac OS X)! Hvorfor, etter din mening, har disse platformene så forskjellige objektfil-formater?
  
  - Linux: ELF
  - MS Windows: PE
  - Mac OS X: Mach-O
  
  Vi tror disse plattformene har forskjellige objektfil-formater fordi forskjellige plattformer har forskjellige måter å lese og kjøre filer/programmer på.

2. Gå gjennom https://tour.golang.org/basics/1 Hvilke forskjeller ser du i forhold til programmeringsspråket Java? (forutsetter at alle er kjent med Java, hvis ikke, så kan man også sammenligne med andre programmeringsspråk)
- Golang bruker func for å initialisere metodene
- Golang bruker ikke semikolon
- Golang bruker fmt istedenfor System.out. for å printe ut. De bruker mer forkortelser i forhold til Java
- Golang importerer hele pakken med "package main"

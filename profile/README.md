# Računalništvo v oblaku 2022/2023

## Projekt: Primerjalnik cen izdelkov

### Člani skupine

* Žan Kogovšek

### Opis projekta

Primerjalnik cen izdelkov omogoča uporabnikom primerjanje cen različnih izdelkov. Aplikacija omogoča prikaz cen različnih izdelkov po različnih trgovinah in ustvarjanje košarice. S pomočjo slednje lahko uporabniki enostavno izračunajo ceno vseh izdelkov v košarici. Nenazadnje lahko uporabniki posamezni izdelek dodajo tudi med priljubljene, kjer mu dodelijo stopnjo priljubljenosti in kratek komentar zakaj je bil izdelek dodan med priljubljene.

### Ogrodje in razvojno okolje

* Ogrodje: Apache Maven
* Razvojno okolje: IntelliJ IDEA Ultimate (Java 19)

### Shema arhitekture in shemo interakcij med mikrostoritvami

![Entiteno relacijski diagram](../diagrami/Konceptualni%20diagram%20-%20RSO.drawio.png "Entitetno relacijski diagram")

### Seznam interakcij

* Mikrostoritev za izdelke
    * CRUD operacije nad izdelki
    * Primerjava med trgovinami
* Mikrostoritev za košarico
    * CRUD operacije za košarico
    * Izračun cene košarice
* Mikrostoritev za priljubljene izdelke
    * CRUD operacije nad priljubljenimi izdelki

### Primeri uporabe

![Diagram primerov uporabe](../diagrami/Primeri%20uporabe%20-%20RSO.drawio.png "Diagram primerov uporabe")
# PVA4 - Programování a vývoj aplikací
## Lekce 12: Projekt - Objednávky - zobrazení

## Obsah

### 0
Přepněte se do minulého repozitáře cvičení 11 repozitáře, proveďte export databáze a odešlete commit. Poté se vraťte do Cvičení 12

### 1
V databázi sandbox vytvořte tabulku `objednavky` (číslo objednávky, datum vytvoření)
Tabulku objednavky propojte relací s tabulkou uzivatele z minulého cvičení. Využijte relaci 1:N

Ukázka obsahu tabulky uživatelů:
```
Pana Kotta
Lorad Obchodník
Onapa Šetřílková
```

Do tabulky objednávky vložte:
```
Pana Kotta - 2 objednávky
Lorad Obchodník - 1 objednávku
Onapa Šetřílková - žádnou objednávku
```

### 2
Vytvořte tabulku pro ukládání obsahu objednávky. Tabulka bude obsahovat mimo textové informace o položce objednávky, taktéž množství, cenu za kus, cenu celkem. Nezapomeňte v tabulce mít relaci na objednávku.

Naplňte tabulku libovolnými  záznamy, aby každá objednávka měla alespoň jednu položku.

### 3 
Proveďte export SQL databáze a uložte jej do souboru `dump.sql`.

### 4
Naprogramujte php script, který bude zobrazovat seznam všech objednávek. Tabulka bude obsahovat sloupce:
* Jméno a příjmení zákazníka
* Číslo objednávky
* Datum objednávky


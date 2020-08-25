# Test-Data
Tento jednoduchý program generuje datový soubor pro další účely, například pro odesílání zpráv přes message sender za účelem testování.
Výstupem je datový soubor(JSON) ve formátu [attribute_name]=[value], přičemž název atributu i jeho hodnota je závislá od vstupního konfiguračního souboru uloženého v excelové tabulce.

První sloupec v konfigurační tabulce definuje název atributu.
Druhý sloupec určuje datový typ.
Třetí hodnotu atributu.
Například person_name, string, John.
Pokud není u atributu ve sloupci hodnota uvedena, program jí vygeneruje v závislosti na datovém typu.

#In progress


## Čtenářský deník v LaTeXu

Šablona pro čtenářský deník, kompiluje se LuaLaTeXem

- Novou knihu: zkopíruj libovolný soubor v knihy/, přejmenuj ho RRRR-MM-DD-nazev.tex (určuje pořadí).
- Obálku dej do obalky/ (jpg/png) a do souboru napiš obalka=nazev-souboru.
- Struktura je navržena tak, aby bylo možné například v TexStudiu mít otevřenou a editovat jednu knihu, kterou lze nezávisle na ostatních kompilovat, přičemž se načte šablona se všemi příkazy. 
- Celý deník se nakonec zkompiluje i s úvodní stránkou a obsahem:  lualatex ctenarsky-denik.tex  (dvakrát kvůli obsahu)

Barevné téma lze snadno změnit úpravou barvy <code>\definecolor{denik}{HTML}{2E5E8C}</code> v souboru <code>ctenar.sty</code>, stejně tak tam lze upravit i použité fonty.

## Čtenářský deník v LaTeXu

Šablona pro čtenářský deník, kompiluje se LuaLaTeXem

- Novou knihu: zkopíruj libovolný soubor v knihy/, přejmenuj ho RRRR-MM-DD-nazev.tex (určuje pořadí).
- Obálku dej do obalky/ (jpg/png) a do souboru napiš obalka=nazev-souboru.
- Jednu knihu zkompiluješ sám:  lualatex knihy/soubor.tex   (nebo tlačítko Recompile ve svém editoru)
- Celý deník:  lualatex ctenarsky-denik.tex  (dvakrát kvůli obsahu)

Barevné téma lze snadno změnit úpravou barvy <code>\definecolor{denik}{HTML}{2E5E8C}</code> v souboru <code>ctenar.sty</code>, stejně tak tam lze upravit i použité fonty.

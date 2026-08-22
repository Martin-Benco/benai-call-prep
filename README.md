# Martin Sales — Command Center

Dashboard na prípravu obchodných hovorov a osobný zoznam úloh.

`index.html` generuje Claude a pushuje sem. Vercel po každom pushi nasadí novú verziu.

## Úlohy
Úlohy sa ukladajú automaticky v prehliadači (localStorage) a prežijú
zavretie okna aj reštart počítača. Sú viazané na tento prehliadač
a toto zariadenie.

Tlačidlo "Uložiť zálohu" stiahne úlohy ako .json súbor.
Tlačidlo "Obnoviť zo zálohy" ich načíta späť (napr. na inom počítači).

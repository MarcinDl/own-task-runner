#npm

przykładowy task runner.

Zainstalować komendą * *npm install* *

Uruchamiany komendą: * *npm run watch* *
s

**ESlint:**
- poprawne formatowanie, zgodne z tym ustawionym w EditorConfig (wcięcia, zakończenia linii),
- używamy pojedynczych cudzysłowów,
- stawiamy średniki na końcu każdej linii (poza wyjątkami).
Aby uruchomić tylko eslint wpisujemy * *npm run test:js* *

**EditorConfig:**

Zainstalować (dla VS Code): https://marketplace.visualstudio.com/items?itemName=chrisdias.vscodeEditorConfig

- stosowanie wcięć (indentacji) w postaci 2 spacji,
- kodowanie pliku utf-8 i unixowe zakończenia linii,
- usuwanie spacji na końcu linii,
- dodawanie pustej linii na końcu pliku.

Uruchomienie: * *po zainstalowaniu działa samoczynnie* *

**StyleLint:**
- poprawne formatowanie, zgodne z tym ustawionym w EditorConfig (wcięcia, zakończenia linii),
- wymagana spacja po dwukropku,
- wymagana nowa linia po średniku,
- nie więcej niż dwie puste linie bezpośrednio po sobie,
- maksymalne zagnieżdżenie 4 poziomów (nie licząc pseudoklas),
- nie używamy znaku & bez potrzeby,
- nie definiujemy wielokrotnie tej samej zmiennej.

Uruchomienie: * *npm run test:scss* *

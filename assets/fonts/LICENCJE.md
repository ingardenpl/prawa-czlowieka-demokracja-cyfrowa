# Licencje czcionek

Pliki `.woff2` w tym folderze pobrano 11.11.2026 z Google Fonts (podzbiory `latin` i `latin-ext`, potrzebne dla polskich znaków). Strona ładuje je lokalnie przez `@font-face` w `index.html`, bez żądań do zewnętrznych serwerów.

| Krój | Odmiany w folderze | Autor | Licencja |
|---|---|---|---|
| Chakra Petch | 500, 600, 700 | Cadson Demak | SIL Open Font License 1.1 |
| IBM Plex Sans | zmienna (używane 400, 500, 600) | IBM Corp., Mike Abbink, Bold Monday | SIL Open Font License 1.1 |
| IBM Plex Mono | 400, 500, 600 | IBM Corp., Mike Abbink, Bold Monday | SIL Open Font License 1.1 |
| IBM Plex Serif | 400, 400 kursywa, 600 | IBM Corp., Mike Abbink, Bold Monday | SIL Open Font License 1.1 |

Tekst licencji: https://openfontlicense.org (SIL Open Font License, wersja 1.1). Licencja pozwala używać, osadzać i rozpowszechniać czcionki razem z innym oprogramowaniem i dokumentami. Nie wolno sprzedawać samych plików czcionek ani używać zastrzeżonych nazw krojów dla zmienionych wersji.

Nazwy plików: `Krój-<n|it><waga>-<podzbiór>.woff2`; IBM Plex Sans to jeden plik zmienny na podzbiór (`IBMPlexSans-var-*`).

## Styl grecki (25.11.2026)

Pliki dodane 25.11.2026 dla stylu greckiego (klasa `th-hellas`, klawisz Y przełącza na styl silnika). Pobrane z repozytorium google/fonts na GitHubie (katalog `ofl/`), przekonwertowane do woff2 narzędziem fontTools bez podzbiorów (pełne pliki: łacina z polskimi znakami, greka). Sprawdzone znaki: ą ę ł ń ó ś ź ż Ą Ę Ł Ń Ó Ś Ź Ż we wszystkich; greka Α–Ω tylko w Alegreya, Alegreya Sans i GFS Didot; stigma Ϛ (6 w numeracji greckiej) tylko w GFS Didot, dlatego litery przystanków są składane GFS Didot.

| Krój | Plik | Do czego | Autor | Licencja |
|---|---|---|---|---|
| Cinzel | `Cinzel-var.woff2` (zmienny 400–900) | kickery, etykiety, tytuł na mapie, karty przystanków | Natanael Gama | SIL Open Font License 1.1 |
| Marcellus SC | `MarcellusSC-n400.woff2` | nagłówki h1/h2 (kapitaliki) | Brian J. Bonislawsky (Astigmatic) | SIL Open Font License 1.1 |
| Alegreya | `Alegreya-var.woff2`, `Alegreya-it-var.woff2` | tekst szeryfowy (cytaty, zdania wiodące) | Juan Pablo del Peral (Huerta Tipográfica) | SIL Open Font License 1.1 |
| Alegreya Sans | `AlegreyaSans-n400/n500/n700/it400.woff2` | tekst główny, HUD, tabele | Juan Pablo del Peral (Huerta Tipográfica) | SIL Open Font License 1.1 |
| GFS Didot | `GFSDidot-n400.woff2` | litery greckie przystanków (Α Β Γ Δ Ε Ϛ Ζ Η Θ), znaki wodne | Greek Font Society | SIL Open Font License 1.1 |

Źródła: github.com/google/fonts/tree/main/ofl/{cinzel, marcellussc, alegreya, alegreyasans, gfsdidot}; teksty licencji OFL.txt w tych katalogach (copyright: The Cinzel Project Authors; Astigmatic; The Alegreya Project Authors; The Alegreya Sans Project Authors; Greek Font Society 2007).

Teksty licencji kopiowane obok: `OFL_Cinzel.txt`, `OFL_MarcellusSC.txt` (ten sam tekst co dla Marcellus), `OFL_Alegreya.txt`, `OFL_AlegreyaSans.txt`, `OFL_GFSDidot.txt`.

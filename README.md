# De Lokale Ziel — reisblog

Statische reisblog: één foto, één woord, de ziel van de dag.

## Publiceren op GitHub Pages

1. Maak op github.com een nieuwe repository (bijv. `de-lokale-ziel`).
2. Upload alle bestanden uit deze map (inclusief de map `images/`).
   Dat kan via de website: *Add file → Upload files*.
3. Ga naar *Settings → Pages*.
4. Kies bij *Source*: **Deploy from a branch**, branch **main**, map **/ (root)**. Sla op.
5. Na 1-2 minuten staat de site live op
   `https://<jouw-gebruikersnaam>.github.io/de-lokale-ziel/`

## Foto's toevoegen

Zet je foto's in de map `images/` met de namen `dag1.jpg` t/m `dag8.jpg`
(zie `images/LEESMIJ.txt`). Ontbreekt een foto, dan toont de site de
kleurgradiënt van die dag — de site werkt dus ook zonder foto's.

## Nieuwe entry toevoegen

Kopieer een bestaande entrypagina, pas woord, tekst, datum en kleuren
aan in de `:root`-variabelen bovenaan, en voeg een kaartje toe aan
`index.html`.

# Grammar City

Otwarte miasto 3D w stylu GTA do nauki gramatyki angielskiej. Chodzisz po mieście (albo „pożyczasz” auto), docierasz do znaczników misji, a każda misja to quiz z jednego zagadnienia gramatycznego.

**Zagraj:** https://dandeliant.github.io/grammar-city/

Gra jest aplikacją PWA — w Chrome/Edge kliknij „Zainstaluj aplikację” na ekranie startowym (lub ikonę instalacji w pasku adresu). Po pierwszym uruchomieniu działa także offline.

## Misje

| Poziom | Misje |
| --- | --- |
| A1 | to be · przedimki · there is/are · Present Simple · zaimki |
| A2 | Present Continuous · Past Simple · stopniowanie · policzalne/niepoliczalne · will/going to |
| B1 | Present Perfect · czasowniki modalne · przyimki · gerund/bezokolicznik |
| B2 | tryby warunkowe · strona bierna · mowa zależna · zdania względne |
| Finał | egzamin w ratuszu — pytania ze wszystkich tematów |

180 pytań w trzech typach (wybór, wpisywanie, rozsypanka), wyjaśnienia po polsku, próg zaliczenia 70%. Postęp zapisuje się w przeglądarce.

## Sterowanie

`WASD` ruch/jazda · mysz kamera · `Shift` sprint · `Spacja` skok/ręczny · `F` wsiądź/wysiądź · `E` misja · `M` mapa i GPS · `H` pomoc · `N` dźwięk

## Uruchomienie lokalne

```bash
python -m http.server 8765
```

Potem otwórz http://localhost:8765. Pytania i misje są w `questions.js`, silnik gry w `game.js` (Three.js r128).

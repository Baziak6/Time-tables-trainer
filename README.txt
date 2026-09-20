MATEMATYCZNA PRZYGODA v6.0

NOWOŚCI:
- automatyczny system aktualizacji PWA: aplikacja sprawdza nową wersję przy uruchomieniu i co 60 sekund; gdy aktualizacja jest gotowa pokazuje przycisk „Zaktualizuj teraz”
- przycisk Menu oraz „Aktualizuj” są zawsze na górze ekranu
- diamenty są rzadszą walutą o większej wartości; wiele wyjątkowych przedmiotów kupuje się za diamenty
- 3 pełne rysunkowe postacie: dziewczynka, chłopiec i koci bohater
- stroje są częścią rysunku postaci i dopasowują się do sylwetki
- bogatsze tła pokoju oraz kolorowe, fantazyjne menu
- gry: Łap wynik, Memory, Kryształowe wyzwanie
- zachowane: stacje, mieszane działania, brakująca liczba, błędy, 3 poprawne odpowiedzi do opanowania, czas malejący wraz z trudnością

AKTUALIZACJA NA GITHUB:
1. Rozpakuj ZIP.
2. W repozytorium GitHub podmień index.html, sw.js, manifest.json, icon.svg i README.txt plikami z folderu times-tables-app.
3. Zrób Commit changes.
4. Pierwsze przejście ze starej wersji v5 do v6 może nadal wymagać jednorazowego odświeżenia/wyczyszczenia starego cache, ponieważ stary service worker v5 nie miał nowego systemu aktualizacji.
5. Po uruchomieniu v6 kolejne wersje powinny być wykrywane automatycznie. Dane gry pozostają w localStorage i nie są usuwane przez aktualizację service workera.

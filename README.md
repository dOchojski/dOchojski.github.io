# Daniel Ochojski – przekierowanie

Strona Creativ Apps działa pod adresem **https://creativapps.pl** (hosting home.pl).

To repozytorium (GitHub Pages, gałąź `main`) zawiera tylko stronę przekierowującą:
`index.html` i `404.html` kierują na `https://creativapps.pl` z zachowaniem ścieżki,
`rel="canonical"` wskazuje nowy adres, a `noindex` usuwa stary adres z wyników wyszukiwania.
Pełna wersja strony jest w historii gita (commit 257acc7).

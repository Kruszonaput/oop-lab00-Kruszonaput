# Moje wykonanie Lab00

- Login GitHub / pseudonim: Kruszonaput
- System i terminal (np. Windows + WSL Ubuntu): Windows + PowerShell
- Edytor / IDE: Antigravity IDE
- Wersja Git: 2.56
- Wersja kompilatora C++: g++ 16.2.0 (MSYS2)
- Wersje java i javac: 17.0
- Link do pierwszego PR (uzupełnij w zadaniu 5): ...

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! Kruszonaput
```
Wynik programu Java:
```text
Hello from Java! Kruszonaput
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: ...
- Przyczyna oraz sposób naprawy: ...
- Commit z błędem (SHA lub link): ...
- Czy Actions pokazały błąd, a po naprawie sukces? ...

## Krótkie odpowiedzi
1. Co różni commit od push? 
commit tylko zapisuje nową wersję plików u mnie na komputerze (na dysku). Dopiero Push bierze te zapisane commity i faktycznie wysyła je przez neta na serwer GitHuba, żeby inni mogli je zobaczyć.

2. Dlaczego po scaleniu PR wykonuję lokalnie pull? 
 Bo jak kliknę "Merge" na stronie GitHuba, to główna gałąź main na serwerze się zaktualizuje o nowy kod, ale mój folder na kompie o tym nie wie. Robię git pull, żeby zaktualizować mojego lokalnego maina o te zmiany ze strony.

3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? 
Potwierdza tylko to, że kod kompiluje się na chmurowej maszynie GitHuba. Nie potwierdza jednak tego, że zadanie jest logicznie poprawne, ani tego, czy mam dobrze zainstalowane narzędzia u siebie na laptopie.



## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...

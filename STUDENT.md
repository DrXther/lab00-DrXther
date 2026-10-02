# Moje wykonanie Lab00

- Login GitHub / pseudonim: DrXther
- System i terminal (np. Windows + WSL Ubuntu): Windows 11 + WSL Ubuntu | Linux mint + Gnome 3
- Edytor / IDE: Visual studio code
- Wersja Git: 2.43
- Wersja kompilatora C++: 13.3
- Wersje java i javac: 21.0.12.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/DrXther/lab00-DrXther/pull/2

## Uruchomienie lokalne
Wynik programu C++:
```
Hello from C++! Author: DrXther
```
Wynik programu Java:
```
Hello from Java! Author: DrXther
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: 7: error: expected `;` before `return`
- Przyczyna oraz sposób naprawy: sam usunąłem ten średnik zgodnie z treścią zadania. Zgodnie z treścią zadania dodałem go z powrotem.
- Commit z błędem (SHA lub link): https://github.com/DrXther/lab00-DrXther/pull/2/changes/83fbda0d056140cc4403657907bd7ade24bbd988
- Czy Actions pokazały błąd, a po naprawie sukces? tak

## Krótkie odpowiedzi
1. Co różni commit od push? commit jest paczką którą wysyłamy, push jest odpowiedzialny za jej wysłanie.
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? By upewnić się że zawartość plików lokalna zgadza się z zawartością plików w repo.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza poprawną kompilacje. Poprawna kompilacja nie oznacza że program działa jak należy (n.p działa ale podaje zły wynik)

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: brak internetu ze względu na błąd własny, rozwiązany za pomocą pendrive'a za pomocą którego przenosiłem dane między komputerem z internetem (ale bez g++), a laptopem bez internetem, (ale z g++)

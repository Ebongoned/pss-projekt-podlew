# Kolekcje Postmana

Plan Free Postmana obejmuje jedną osobę, dlatego zespół dzieli kolekcje przez to repozytorium.

1. Eksportujemy kolekcje w formacie **JSON v2.1** (Postman: *More → Export collection → Export JSON*).
2. Jedna osoba — jeden plik. Cudzy plik zmieniasz tylko po uzgodnieniu z jego właścicielem.
3. W plikach środowisk (`*.postman_environment.json`) hasła, tokeny i klucze mają puste wartości.
   Prawdziwe wartości wpisujesz tylko u siebie w Postmanie.
4. Kopie z prawdziwymi sekretami trzymasz w `postman/prywatne/` — ten katalog jest w `.gitignore`.
5. Przed każdym commitem przeglądasz zmiany: `git diff --staged`.

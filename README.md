# Lab 04: Tablice

| Termin oddania | Punkty     |
|----------------|:-----------|
|    29.12.2024 23:00 |   10        |

--- 
Przekroczenie terminu o **n** zajęć wiąże się z karą:
- punkty uzyskanie za realizację zadania są dzielone przez **2<sup>n</sup>**.

--- 
## Zadanie 1 [4 pkt]
1. Zaimplementuj strukturę, reprezentującą punkty na płaszczyźnie w kartezjańskim układzie współrzędnych. 
Prócz reprezentacji współrzędnych punktu, stuktura powinna posiadać metodę `toString` o funkcjonalności podobnej do prezentowanej na wykładzie.
1. Dla tak przygotowanej struktury napisać funkcję:
   - obliczającą odległość dla dwóch zadanych punktów
   - sprawdzającą czy trzy punkty tworzą trójkąt z zadaną dokładnością
   - dla zbioru (tablicy) punktów na płaszczyźnie wskazać punkty nabardziej oddalone od siebie.

## Zadanie 2 [6 pkt]
Wykorzystując funkcje, tablice i struktury napisać program modelujący następującą sytuację:
1. Dziekanat posiada rejestr studentów. Każdy student posiada numer, imię, nazwisko, bieżący semestr i dla każdego semestru listę przedmiotów do zaliczenia.
Przedmiot składa się z nazwy, punktów ECTS i listy ocen uzyskanych z tego przemiotu. Program powinien umożliwiać operacje CRUD na powyższych danych (CRUD = Create, Read, Update, Delete).
2. Dziekanat potrzebuje funkcji pozwalających:
   - zaliczyć studentowi bieżący semestr i przenieść na kolejny (co zrobić z absolwentami?)
   - przygotować listę rankingową studentów do przyznania stypendiów (oceny z przedmiotów są ważone punktami ECTS)
3. Po zakończonej sesji dziekanat przygotowuje statystyki sesji:
   - dla każdego przedmiotu rozkład ocen zarówno podstawowych jak i poprawkowych
   - dla każdego studenta średnie semestrów i przedmiotów.

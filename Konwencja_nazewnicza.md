`<project short name>` - małe litery, skrócona nazwa projektu składająca się z 2-4 liter

`<environment>` - typ środowiska: produkcja - prod, developerskie - dev

`<number>` - liczba

## Grupa Zasobów
* Ograniczenie długości: 1-90
* Poprawne znaki: alfanumeryczne, podkreślenia, nawiasy, łącznik, kropka (za wyjątkiem końców) i znaki Unicode
* Konwencja nazewnicza: `<project short name>-<environment>-rg`

## VNET
* Ograniczenie długości: 2-64
* Poprawne znaki: alfanumeryczne, łącznik, podkreślenie i kropka
* Konwencja nazewnicza:`<project short name>-vnet<number>`

## Maszyn Wirtualna
* Ograniczenie długości: 1-15 (Windows), 1-64 (Linux)
* Poprawne znaki: alfanumeryczne i łącznik
* Konwencja nazewnicza:`<project short name>-vm<number>`

## Dysk
* Ograniczenie długości: 3-24
* Poprawne znaki: alfanumeryczne
* Konwencja nazewnicza:`<vm name without hyphens>st<number>`

## Konta składowania danych
* Ograniczenie długości: 3-24
* Poprawne znaki: alfanumeryczne
* Konwencja nazewnicza:`<project short name>sa<number>`

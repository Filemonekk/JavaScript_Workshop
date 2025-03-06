# Modo Shop

Modo Shop to interaktywna aplikacja w JavaScript umożliwiająca użytkownikowi wybór kategorii odzieży, konkretnego produktu oraz jego rozmiaru. Projekt działa w przeglądarce i wykorzystuje `prompt` do komunikacji z użytkownikiem.

## Opis projektu
Aplikacja działa na zasadzie dialogu w oknie przeglądarki. Użytkownik jest kolejno pytany o:
1. **Wybór kategorii** (np. buty, spodnie, koszule, kurtki, akcesoria).
2. **Wybór konkretnego produktu** w wybranej kategorii.
3. **Wybór rozmiaru** dostępnego dla wybranego produktu.

Wszystkie dostępne produkty znajdują się w obiekcie `inventory`, który przechowuje informacje o nazwie, cenie, dostępnych kolorach i rozmiarach.

## Struktura projektu
Plik HTML zawiera skrypt JavaScript, który realizuje funkcjonalność wyboru produktów. Skrypt:
- Definiuje obiekt `inventory` przechowujący dostępne produkty.
- Umożliwia użytkownikowi wybór kategorii poprzez `prompt()`.
- Pozwala na wybór konkretnego produktu w wybranej kategorii.
- Prowadzi użytkownika przez proces wyboru rozmiaru.
- Wypisuje w konsoli szczegóły wybranego produktu.

## Autor
Projekt został stworzony jako demonstracja podstawowej interakcji użytkownika z JavaScript.


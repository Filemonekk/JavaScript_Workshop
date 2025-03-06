# Modo Shop
## Autor
Projekt został stworzony jako demonstracja podstawowej interakcji użytkownika z JavaScript.
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







# Przykład listy zakupów
## Autor
Ten prosty projekt listy zakupów został stworzony w celu demonstracji podstawowej manipulacji DOM za pomocą JavaScript.

Ten projekt to prosta interaktywna lista zakupów napisana w HTML, CSS i JavaScript. Umożliwia użytkownikom dynamiczne dodawanie i usuwanie pozycji z listy zakupów.

## Funkcje
- Użytkownik może wpisać nowy element do pola tekstowego.
- Kliknięcie przycisku "Dodaj pozycję" powoduje dodanie wpisanego elementu do listy.
- Każdy dodany element pojawia się w nieuporządkowanej liście (`<ul>`) wraz z przyciskiem "Usuń".
- Kliknięcie przycisku "Usuń" usuwa dany element z listy.

## Struktura projektu
### HTML (`index.html`)
- Dokument zawiera nagłówek (`<h1>`) oraz pole tekstowe (`<input>`) do wprowadzania elementów.
- Przycisk umożliwia dodanie wpisanej pozycji do listy.
- Nieuporządkowana lista (`<ul>`) służy jako kontener dla pozycji listy zakupów.

### CSS
- Każdy element listy (`<li>`) ma margines dla lepszej czytelności.
- Przyciski są stylizowane z mniejszym rozmiarem czcionki i innym kolorem, aby odróżnić je od głównej treści.

### JavaScript
Skrypt umożliwia interaktywną funkcjonalność:
1. **Nasłuchiwanie kliknięcia przycisku „Dodaj”**
   - Pobiera tekst z pola wejściowego.
   - Czyści pole wejściowe po pobraniu wartości.
   - Tworzy nowy element listy (`<li>`) zawierający:
     - Element `<span>` do wyświetlania tekstu.
     - Przycisk "Usuń".
   - Dodaje nowy element do nieuporządkowanej listy (`<ul>`).
   
2. **Funkcjonalność usuwania**
   - Każdy element listy ma przycisk usuwania.
   - Kliknięcie przycisku „Usuń” powoduje usunięcie danego elementu z listy.




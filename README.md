# Dokumentacja projektu NotesApp

## Opis projektu
NotesApp to aplikacja służąca do zarządzania notatkami. Umożliwia użytkownikom logowanie, przypominanie hasła, oraz przeglądanie i tworzenie notatek.

## Technologie
Aplikacja została zbudowana w oparciu o platformę Android.

- Java
- Firebase 

## Baza danych

Do projektu zostały zaimportowane pakiety Firebase. Baza danych została utworzona i zaimplementowana według instrukcji udostępnionej na stronie [Firebase](https://firebase.google.com/).
##### Wykorzystane technologie:
- Firebase Authentication: do uwierzytelniania użytkowników.
- Firebase Firestore: do przechowywania i zarządzania danymi aplikacji.
 
## Struktura projektu
Projekt składa się z plików, takich jak:
- MainActivity
- createnote
- notesactivity
- notedetails
- editnoteactivity
- signup
- ForgotPassword
- firebasemodel

### Model danych
W pliku MainActivity.java znajduje się główna logika aplikacji, w tym obsługa interfejsu użytkownika, logowanie, oraz sprawdzanie weryfikacji adresu e-mail. Jest to kluczowy komponent projektu odpowiedzialny za autoryzację użytkowników i zarządzanie ich dostępem do funkcji aplikacji.

## Instalacja i uruchomienie

Aby uruchomić projekt, wykonaj następujące kroki:

1. **Pobierz kod źródłowy**: Sklonuj repozytorium lub pobierz kod źródłowy jako archiwum ZIP.

2. **Otwórz projekt w środowisku deweloperskim**: Uruchom swój ulubiony edytor kodu lub środowisko deweloperskie, takie jak Android Studio.

3. **Ustaw konfigurację projektu**: Upewnij się, że masz zainstalowane odpowiednie SDK dla projektu (np. Android SDK) i skonfiguruj środowisko według instrukcji dostarczonych przez producenta.

4. **Zainstaluj zależności**: Jeśli projekt używa jakichkolwiek zależności, upewnij się, że są one zainstalowane. Jeśli używasz systemu zarządzania zależnościami, wykonaj odpowiednie polecenia instalacyjne.

5. **Uruchom aplikację**: Po skonfigurowaniu projektu i zainstalowaniu zależności, możesz uruchomić aplikację na emulatorze lub urządzeniu docelowym za pomocą funkcji dostępnej w swoim środowisku deweloperskim.

Po wykonaniu tych kroków, aplikacja powinna być gotowa do uruchomienia i testowania na emulatorze lub urządzeniu docelowym.

## Autor 
Paulina D. 

## Licencja

Ten projekt jest objęty [licencją MIT](https://couto.mit-license.org/). Szczegółowe informacje można znaleźć w pliku [LICENSE](LICENSE).

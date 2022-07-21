# Notatka ze spotkania z klientem:
**Autorka: [OllaWilk](https://github.com/OllaWilk)**
- Admin dodaje/rejestruje wszystkich użytkowników (usera/hrowca). Można zrobić formularz dla admina.
- Robimy apke na widok desktopowy.
- User i HR nie mają widoku rejestracji.
- User i HR może mieć funkcje odzyskania hasła
- Flow:
```
1. Backend wysyła link aktywacyjny na mail usera/hr
2. po kliknięciu userowi/HR wyświetla się widok z polem do wpisania hasła
3. po wpisaniu hasła przenosi się do swojego widoku.
```
- Task do zrobienia na początku. Rozpisać strukturę bazydanych
- **Klient rozlicza nas w czwartki.** Na YT publikujemy dema tego co zrobiliśmy i jak działa apka.
- **Token ma być generowany jako UUID (lub to co wybierzemy) i zapisywany w BD. Po potwierdzeniu rejestracji czyszczony.**

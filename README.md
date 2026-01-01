# Gmail Auto-Responder Workflow

Prosta automatyzacja n8n do automatycznego potwierdzania odbioru wiadomości.

## 📋 Funkcje
- **Monitoring:** Sprawdza Gmaila co 60 sekund.
- **Filtr:** Reaguje na e-maile zawierające frazę `SZUKANE_HASŁO`.
- **Auto-reply:** Wysyła zwrotną informację o przetwarzaniu wiadomości.

## ⚙️ Instalacja
1. Zaimportuj plik JSON do **n8n**.
2. Podepnij własne konto przez **Gmail OAuth2**.
3. W węźle `Gmail Trigger` ustaw słowo kluczowe w polu `q`.

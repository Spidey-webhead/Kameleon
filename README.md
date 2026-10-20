 Kameleon 
Wieloosobowa gra online oparta na dedukcji i ukrytych rolach z wykorzystaniem mechanizmów NLP.

---

 Struktura Monorepo i Podzia³ Ról

- **frontend/** - Osoba 3 (React: host, guest, shared)
- **backend/** - Osoba 3 / Daria (Spring Boot: room, session, websocket, persistence, game-engine-client)
- **game-service/** - Osoba 5 / Przemek (Python FastAPI + Word2Vec: engine, nlp, api, tests)
- **simulations/** - Osoba 4 / Wojtek (Python SimPy: agents, scenarios, experiments, reports)
- **infrastructure/** - Osoba 2 / Natalka (Docker, compose.yaml, monitoring)
- **.github/workflows/** - Osoba 2 / Natalka (Automatyzacja CI/CD)
- **docs/** - Osoba 1 / Kuba (Dokumentacja projektu)

---

 Jak uruchomiæ projekt 
1. Sklonuj repozytorium:
   git clone https://github.com/Spidey-webhead/Kameleon.git
   cd Kameleon

2. Uruchom œrodowisko za pomoc¹ Docker Compose:
   docker compose -f infrastructure/compose.yaml up --build

---

 Zasady Wspó³pracy

- **G³ówna ga³¹Ÿ:** main (stabilna wersja produkcyjna)
- **Tworzenie ga³êzi:** feature/opis-funkcji lub fix/opis-bleda
- **Pull Requesty:** Wymagany opis zmian i zatwierdzenie przez co najmniej jedn¹ osobê z zespo³u.

\# Dishy 🍲



> Because your plate should be as smart as your tech stack.



\*\*Dishy\*\* to inteligentny, dwufazowy system rekomendacji posiłków oparty na kontekście, nawykach oraz zaawansowanym urozmaicaniu diety przy użyciu algorytmu Multi-Armed Bandit.



\---



\## 🛠️ Architektura i Stack Technologiczny



System został zaprojektowany w architekturze mikroserwisów (Monorepo):



\*   \*\*`dishy-core`\*\* (Java / Spring Boot) – Serwer główny, logika biznesowa, transakcje, zarządzanie pamięcią podręczną.

\*   \*\*`dishy-brain`\*\* (Python / FastAPI) – Silnik rekomendacji AI, wektoryzacja tekstu (NLP), reranking danych.

\*   \*\*`dishy-mobile`\*\* (Dart / Flutter) – Nowoczesna i płynna aplikacja kliencka.

\*   \*\*Infrastruktura:\*\* PostgreSQL (dane relacyjne), Redis (cache stanu dnia), RabbitMQ (komunikacja asynchroniczna).



\---



\## 🚀 Jak zacząć?

\*Projekt w fazie inicjalnej. Wkrótce pojawi się konfiguracja Docker Compose.\*


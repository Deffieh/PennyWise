# [PennyWise] 💰

Un'applicazione Full-Stack moderna per il tracciamento delle spese personali, progettata per essere eseguita in ambienti containerizzati (Docker) su infrastruttura domestica (Raspberry Pi / Mini PC).

## 🚀 Obiettivi del Progetto
L'obiettivo di questo progetto è fornire uno strumento leggero e sicuro per la gestione finanziaria, eliminando la dipendenza da servizi cloud esterni e mantenendo la piena sovranità sui propri dati sensibili.

## 🛠️ Tech Stack
* **Backend:** Python 3.11+ con **FastAPI** (Asynchronous API).
* **Frontend:** **Vue.js 3** (Vite, Composition API).
* **Database:** **PostgreSQL** (Scelto per integrità transazionale e supporto JSONB).
* **Infrastructure:** **Docker & Docker Compose** per l'orchestrazione dei servizi.
* **Networking:** Accesso remoto sicuro tramite **Tailscale VPN**.

## 🏗️ Architettura
L'applicazione è strutturata seguendo i principi della *Clean Architecture*, separando la logica di business dall'infrastruttura. 

- **Backend:** Espone API RESTful documentate automaticamente tramite Swagger/OpenAPI.
- **Frontend:** Single Page Application (SPA) reattiva.
- **Database:** Istanza PostgreSQL persistente con volumi Docker.

## 🚦 Come iniziare (Work in Progress)
*(Qui aggiungeremo i comandi `git clone` e `docker-compose up` non appena avremo il codice)*

## 📈 Roadmap
- [ ] Setup ambiente Docker e Database
- [ ] Sviluppo API Core (CRUD Spese)
- [ ] Implementazione Frontend con Vue.js
- [ ] Dashboard con grafici e statistiche
- [ ] Sistema di backup automatizzato su Nextcloud
# 📄 Test Plan – QA Agile Project

## 🎯 Obiectiv

Scopul acestui plan este testarea completă a aplicației web prin metode manuale, automate și API. Testele se bazează pe user stories definite în Jira, în cadrul proiectului QFP.

## 🧩 Epicuri & Zone testate

### 1. Autentificare și Managementul Contului (Manual)
- [x] Testare câmpuri goale
- [x] Email invalid / valid
- [x] Parolă validă / invalidă
- [x] Redirecționare la autentificare corectă
- [x] Logout
- [x] Session timeout (opțional)

### 2. E-commerce Workflow (Automat)
- [x] Vizualizare listă produse
- [x] Adăugare produs în coș
- [x] Afișare produse în coș
- [x] Modificare cantitate produs
- [x] Ștergere produs
- [x] Golire completă coș
- [x] Calcul total comandă
- [x] Persistență coș la refresh
- [x] Finalizare comandă
- [x] Confirmare comandă

### 3. Navigare și UI (API + UI)
- [x] Navigare prin meniu (Forms, Buttons)
- [x] Dropdown-uri
- [x] Deschidere pagini/taburi noi
- [x] Responsivitate
- [x] Compatibilitate Chrome, Firefox, Edge

## 🧪 Tipuri de testare

- ✅ Testare funcțională (manual + automată)
- ✅ Testare API (GET, POST, 404)
- ✅ Testare UI automatizată
- ⏳ Testare negativă (parolă greșită, email invalid)
- 🌐 Testare compatibilitate browser

## 📌 Observații

- Starea de autentificare salvată în `fixtures/storageState.json`
- Raportare buguri și taskuri direct în Jira (QFP board)
- Structura proiectului reflectă fiecare Epic din Jira

## 📍 Concluzie

Testarea a fost realizată în etape Agile (sprinturi scurte). Documentația și codul sunt organizate în GitHub pentru continuitate și revizuire de echipă.

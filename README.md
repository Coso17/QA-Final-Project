# 🧪 QA Automation & Manual Testing – Agile Project

Acest proiect acoperă testarea unei aplicații web prin metode manuale, automate (UI/API) și este organizat în stil Agile folosind Epicuri, user stories și taskuri în Jira.

## 🔧 Tehnologii folosite

- 🎯 Jira – Management Epicuri, Stories și Subtasks
- 🧪 Playwright – Testare automată UI
- 📬 Postman – Testare API (ex: Reqres)
- 📝 Markdown – Documentație testare (plan, stories, checklist)
- 🗃️ GitHub – Versionare și colaborare

## 📂 Structura proiectului

📁 proiect/
├── docs/
│   ├── test-plan.md
│   └── epics.md
├── tests/
│   ├── api/
│   ├── ui/
│   └── playwright.config.js
├── fixtures/
│   └── storageState.json
├── postman/
│   └── reqres_collection.json
└── README.md

## 📌 Epicuri Jira (scurt rezumat)

### 1. `[Manual Testing] Autentificare și Managementul Contului`
> Testarea login-ului, logout-ului și gestionarea sesiunii utilizatorului. Verificări: câmpuri goale, email valid, parolă validă, redirecționare Home, tratament erori.

### 2. `[Automation] E-commerce Workflow`
> Flux complet de cumpărături: vizualizare produse, adăugare în coș, modificare cantitate, ștergere, golire, total comandă, plasare și confirmare comandă.

### 3. `[API Testing] Navigare și Interfață Utilizator`
> Testare navigare prin meniu, butoane, dropdown-uri, interacțiuni hover/click, redirecționări. Comportament responsive și compatibilitate între browsere.

## ✅ Ce am implementat

- [x] Teste manuale pentru autentificare și validări
- [x] Teste automate UI cu Playwright (E-commerce)
- [x] Teste API cu Postman (GET/POST/404)
- [x] Subtask-uri și user stories organizate în Jira
- [x] Documentație completă în `docs/`

## 🏃‍♂️ Cum rulezi testele

```bash
npm install
npx playwright test
```

## ✍️ Autor

- Nume: [Completat de utilizator]
- Proiect: QA Practice (QFP)

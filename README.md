# QA Automation Roadmap — C3 Web App

Dashboard de tracking do progresso de automação de testes do projecto C3, criado a partir dos test cases exportados do [Qase.io](https://qase.io).

## 🔗 Dashboard

👉 **[Ver dashboard ao vivo](https://SEU-USERNAME.github.io/qa-roadmap)**

> Substitui `SEU-USERNAME` pelo teu username do GitHub.

---

## 📊 Estado actual

| Suite | Total | Automatizados | Estado |
|---|---|---|---|
| Dashboard | 2 | 2 | ✅ Done |
| Maintenance | 8 | 8 | ✅ Done |
| Search by image | 5 | 5 | ✅ Done |
| Web Admin | 5 | 2 | 🔄 In progress |
| Instruments | 10 | 2 | 🔄 In progress |
| Packing sets | 5 | 2 | 🔄 In progress |
| Gateway | 2 | 1 | 🔄 In progress |
| Configuration | 8 | 2 | 🔄 In progress |
| Instrument units | 4 | 0 | ⏳ Not started |
| Packed items | 4 | 0 | ⏳ Not started |
| Surgery management | 5 | 0 | ⏳ Not started |
| Cleaning & Sterilization | 2 | 0 | ⏳ Not started |
| Alert Management | 2 | 0 | ⏳ Not started |
| Location Management | 5 | 0 | ⏳ Not started |
| Owners | 2 | 0 | ⏳ Not started |
| Import/Export | 16 | 0 | ⏳ Not started |
| User management | 8 | 0 | ⏳ Not started |

**Progresso geral: 24 / 92 testes (26%)**

---

## 🔄 Como actualizar o dashboard

Quando novos testes forem automatizados, abre o `index.html`, vai à secção **"How to update"** no fundo da página e cola o `QASE_IDS` actualizado do código TypeScript. O dashboard actualiza automaticamente.

Em alternativa, edita directamente o array `suiteData` no `index.html`.

---

## 🗂 Estrutura do repositório

```
qa-roadmap/
├── index.html   # Dashboard completo (HTML + CSS + JS)
└── README.md    # Este ficheiro
```

---

## 🛠 Stack

- HTML / CSS / JavaScript puro — sem dependências externas além do Chart.js
- Dados exportados do Qase.io (CSV)
- Hospedado via GitHub Pages

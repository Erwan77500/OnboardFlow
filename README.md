# OnboardFlow 🚀

**Solution SaaS no-code d'automatisation de l'onboarding RH pour PME**

> Automatisez l'intégralité du parcours d'accueil de vos nouveaux salariés — de J-7 à J+30 — avec de l'IA générative intégrée. Sans coder. Sans DRH dédié. Pour 59€/mois.

---

## 🔗 Liens

| Ressource | URL |
|-----------|-----|
| Application live | [my-onboard-flow.base44.app](https://my-onboard-flow.base44.app) |
| Landing page | [onboardflow-app.netlify.app](https://onboardflow-app.netlify.app) |
| Auteur | [Erwan NKONGO — LinkedIn](https://linkedin.com/in/erwan-nkongo-5b1388160) |

---

## 🛠️ Stack technique

| Outil | Rôle |
|-------|------|
| **Base44** | Génération et hébergement de l'app (AI-native no-code) |
| **Claude API** (Anthropic) | IA générative — emails personnalisés + analyse NPS prédictive |
| **Brevo** | Envoi des emails automatisés (hébergé en France 🇫🇷) |
| **Make.com** | Orchestration des séquences J-7 → J+30 |
| **DocuSeal** | Signature électronique (open source) |
| **Airtable** | Base de données salariés |

> Stack 100% no-code · 0€ de coût fixe jusqu'à 50 clients · RGPD compliant · AI Act compatible

---

## ✨ Fonctionnalités IA

### Brique IA #1 — Email de bienvenue personnalisé
- Déclenchement automatique à la création d'un onboarding
- Claude génère un email unique adapté au poste, secteur et manager
- Coût : ~0,01€ par génération

### Brique IA #2 — Analyse prédictive NPS J+30
- Claude analyse les verbatims du questionnaire J+30
- Génère un score de risque de départ : 🟢 Faible / 🟠 Moyen / 🔴 Élevé
- Visible en badge coloré dans le dashboard admin

---

## 📁 Structure du repo

```
onboardflow/
│
├── landing/
│   ├── index.html          # Landing page V2 (version actuelle)
│   └── index_v1.html       # Landing page V1
│
├── docs/
│   ├── OnboardFlow_Dossier_Final_15pages.pdf   # Dossier complet du projet
│   ├── Projet_OnboardFlow_v2.docx              # Fiche projet (formulaire diplôme)
│   ├── OnboardFlow_Veille_Nocode.docx          # Rapport de veille technologique
│   ├── OnboardFlow_Plan_Sprints_Gantt.docx     # Plan de pilotage Agile
│   └── OnboardFlow_Personas.docx               # Personas utilisateurs (3 profils)
│
├── presentation/
│   └── OnboardFlow_Presentation_V2.pptx        # Pitch deck 11 slides
│
└── assets/
    └── portrait.jpg                             # Photo portrait Erwan NKONGO
```

---

## 📊 Modèle économique

| Clients | MRR | Marge brute |
|---------|-----|-------------|
| 1 client | 59 € | 74% |
| 10 clients | 590 € | ~90% |
| 20 clients | 1 180 € | 97% |
| 50 clients | 2 950 € | 98% |

---

## 🗓️ Roadmap

| Période | Étape |
|---------|-------|
| Juin – Déc. 2026 | Phase bêta — 20 PME françaises testent gratuitement |
| Janvier 2027 | 🚀 Lancement commercial à 59€/mois |
| Q1 2027 | Rapport PDF automatique J+30 + Alertes proactives manager |
| Q2 2027 | Chatbot RH FAQ · Intégration HRIS API |

---

## 🎓 Contexte

Projet réalisé dans le cadre du **Bootcamp AI for Business — Bac+5** (PSTB — Developers Institute, 2025-2026).

Certification obtenue : **Architecture de Gouvernance IA — AI Act & RGPD** (Mai 2026)

**Erwan NKONGO** — Product Builder No/Low-Code & IA | Ex-Payroll Manager (800 collaborateurs)

---

*© 2026 OnboardFlow · Projet no-code avec IA générative · Hébergé en EU*

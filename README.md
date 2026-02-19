# 🚀 Portfolio de Stage - Enyssio Peralta Martinez
 
Bienvenue sur le dépôt de mon portfolio numérique. Ce projet a été réalisé dans le cadre de ma formation en **seconde professionnelle MTNE** (Métiers des Transitions Numériques et Énergétiques) lors de mon stage au sein du **Groupe ESPI**.
 
## 📖 Présentation du Projet

Ce site vitrine a pour objectif de documenter mes compétences acquises, mon parcours scolaire et les missions techniques réalisées en entreprise. Il sert d'interface entre mon profil d'élève et le monde professionnel.
 
---
 
## 🛠️ Spécifications Techniques
 
Le projet repose sur une architecture moderne "Front-end" :
 
* **Structure :** HTML5 sémantique.

* **Style :** [Tailwind CSS v4](https://tailwindcss.com/) (utilisation du CDN pour un développement rapide).

* **Interactivité :** JavaScript (ES6+).

* **Envoi d'e-mails :** [EmailJS](https://www.emailjs.com/) pour la gestion du formulaire sans serveur.

* **Déploiement :** Vercel.

* **Outils IA :** Assistance au code via Gemini et ChatGPT.
 
---
 
## ⚙️ Logique de Gestion (Intégration API)
 
Dans le cadre de l'évolution du projet et de la compréhension des systèmes d'information du Groupe ESPI, l'application suit des règles strictes pour la génération de documents (type bulletins) via l'API Yparéo :
 
### 1. Sélection des paramètres

L'utilisateur interagit avec un formulaire dynamique :

* **Campus :** Liste filtrée par site via l'API.

* **Groupe :** Filtrage par campus avec exclusion automatique des groupes BTS, Césure, RP et DDS.

* **Période d'évaluation :** Année scolaire 2025-2026 uniquement (hors périodes BTS).
 
### 2. Validation de cohérence

Le système empêche les erreurs de saisie grâce à des règles métier :

* Un groupe **ALT** (Alternance) ne peut pas être associé à une période **TP** (Temps Plein).

* Un groupe **TP** ne peut pas être associé à une période **ALT**.
 
---
 
## 📋 Données Récupérées (Structure API Yparéo)
 
Lors de la soumission, l'application interroge l'API en parallèle pour récupérer les jeux de données suivants :
 
| Données | Description |

| :--- | :--- |

| `APPRENANT` | Identité des étudiants du groupe |

| `MOYENNES_UE` | Moyennes par Unité d'Enseignement |

| `MOYENNE_GENERALE` | Score global de chaque étudiant |

| `MATIERE / ECTS` | Détails des matières et crédits associés |

| `OBSERVATIONS` | Appréciations du responsable pédagogique |

| `ABSENCE` | Suivi des retards et absences (justifiées ou non) |

| `GROUPE / SITE` | Informations structurelles du campus |
 
---
 
## 🔧 Installation et Utilisation
 
Pour visualiser ce projet localement :
 
1. Clonez le dépôt :

   ```bash

   git clone [https://github.com/votre-utilisateur/votre-repo.git](https://github.com/votre-utilisateur/votre-repo.git)
 

# synthese-projet.md
## The Interior by Caroline · Paris rive gauche
*Mis à jour : session de lancement — mai 2026*

---

## 1. ÉTAT D'AVANCEMENT

**Phase en cours : Phase 3 — Site en ligne, améliorations & internationalisation**

Le site est en ligne sur `theinteriorbycaroline.fr` (Vercel + GitHub).
Navigation corrigée, logo GreenPartners intégré, photo Caroline mise à jour.

---

## 2. DÉCISIONS ACTÉES

### Identité
- **Nom de marque :** The Interior by Caroline
- **Tagline :** *une signature, un regard, des intérieurs*
- **Positionnement :** Agent indépendant rive gauche (5e, 6e, 7e, 14e) — 500K€–3M€
- **Double compétence :** immobilier résidentiel haut de gamme + architecture d'intérieur
- **Ton de voix :** première personne, discrète, précise, habitée

### Charte graphique
- Palette : `--ink` #1a1612 · `--paper` #f5f0e8 · `--accent` #c47b6c
- Display : Fraunces · Serif : Cormorant Garamond · Sans : Inter · Mono : DM Mono
- Accent saisonnier : terre rosée (printemps/défaut)

### Stack technique
- Hébergement : Vercel (gratuit)
- Repository : GitHub (carolinesim1-gif/theinteriorbycaroline)
- Domaine : theinteriorbycaroline.fr (OVH)
- Analytics : Plausible (à installer)

### Règles de design actées
- Zéro numérotation romaine
- Pas d'email visible nulle part
- GreenPartners = logo uniquement (logo_greenpartners.png), jamais en texte
- Textes courts, pas de redites
- Mobile-first

### Pages produites
| Page | Fichier | Statut |
|------|---------|--------|
| Home | index.html | ✅ En ligne |
| Vendre | vendre.html | ✅ En ligne |
| Acheter | acheter.html | ✅ En ligne |
| Le Journal | le-journal.html | ✅ En ligne |
| À propos | a-propos.html | ✅ En ligne |
| Contact | contact.html | ✅ En ligne |
| Conception | conception.html | ✅ En ligne |
| CSS commun | style.css | ✅ En ligne |
| Mentions légales | mentions-legales.html | ✅ En ligne |
| Confidentialité | confidentialite.html | ✅ En ligne |
| Cookies | cookies.html | ✅ En ligne |
| Honoraires | honoraires.html | ✅ En ligne |

---

## 3. CE QUI RESTE À FAIRE — LISTE EXHAUSTIVE

### A. URGENT — avant tout lancement public

- [ ] **Mentions légales** — remplir les `[À COMPLÉTER]` :
  - SIRET (auto-entrepreneur)
  - Numéro carte T de GreenPartners
  - Organisme de garantie financière
  - Assurance RCP (assureur + n° contrat)
  - Médiateur de la consommation
- [ ] **Honoraires** — remplir le barème (% par tranche de prix)
- [ ] **Vérification mobile** — tester toutes les pages sur iPhone

---

### B. CONTENU — modifications en cours

- [ ] Revoir les textes page par page (non 100% validés)
  - Home · Vendre · Acheter · À propos · Contact · Journal

---

### C. INTERNATIONALISATION

- [ ] **Version anglaise (EN)** — 7 pages principales
  - Fichiers : en/index.html, en/vendre.html, en/acheter.html, en/le-journal.html, en/a-propos.html, en/contact.html, en/conception.html
  - Balises hreflang FR↔EN dans chaque page
  - Switch FR/EN dans la nav à activer

- [ ] **Version italienne (IT)** — 7 pages principales
  - Fichiers : it/index.html etc.
  - Switch FR/EN/IT dans la nav

---

### D. CONNEXION DES FORMULAIRES

Formulaires visuels uniquement pour l'instant — à connecter :

- [ ] **Formulaire estimation** (vendre.html)
  - Outil recommandé : **Formspree** (gratuit, 5 min)
  - Chaque soumission → email avec données vendeur

- [ ] **Formulaire acquéreur** (acheter.html)
  - Idem Formspree ou Brevo
  - Déclenche email automatique de bienvenue signé "caroline"

---

### E. MODULES INNOVANTS

| # | Module | Outil | Complexité | Priorité |
|---|--------|-------|-----------|---------|
| 1 | Chatbot IA (qualification leads 24h/24) | Tidio AI | Faible | ⭐⭐⭐⭐⭐ |
| 2 | Pop-up exit intent (capture avant départ) | Code custom | Faible | ⭐⭐⭐⭐ |
| 3 | Feed Instagram dynamique | Behold.so | Très faible | ⭐⭐⭐ |
| 4 | Séquences email automatiques | Brevo | Moyenne | ⭐⭐⭐⭐ |
| 5 | Calendly embed (rdv intégré) | Calendly | Très faible | ⭐⭐⭐⭐ |
| 6 | Plausible Analytics | Plausible.io | Très faible | ⭐⭐⭐⭐ |
| 7 | Google Business Profile | Google | Faible | ⭐⭐⭐⭐⭐ |
| 8 | Estimateur DVF intelligent | API data.gouv.fr | Haute | ⭐⭐⭐⭐⭐ |

---

### F. SEO

- [ ] Générer et soumettre sitemap.xml à Google Search Console
- [ ] Créer Google Business Profile (business.google.com)
- [ ] Rédiger premiers articles journal (4 catégories définies)
- [ ] Balises hreflang FR/EN/IT après traductions

---

### G. PORTFOLIO CONCEPTION

- [ ] Remplacer les 3 placeholders par photos réelles quand disponibles

---

## 4. ORDRE RECOMMANDÉ

1. Modifier les textes (page par page, session dédiée)
2. Connecter formulaires — Formspree (15 min)
3. Traduction EN (7 pages)
4. Traduction IT (7 pages)
5. Chatbot Tidio (30 min)
6. Pop-up exit intent (30 min)
7. Feed Instagram Behold.so (15 min)
8. Plausible Analytics (5 min)
9. Google Business Profile (30 min)
10. Brevo séquences email (1h)
11. Estimateur DVF — v2

---

## 5. INFOS TECHNIQUES

- **URL live :** theinteriorbycaroline.fr
- **URL Vercel :** theinteriorbycaroline.vercel.app
- **GitHub :** github.com/carolinesim1-gif/theinteriorbycaroline
- **Téléphone :** +33 6 02 10 67 54
- **Instagram :** @theinteriorbycaroline
- **Statut juridique :** Auto-entrepreneur
- **Réseau :** GreenPartners Immobilier (carte T rattachée)
- **Zone :** Paris 5e, 6e, 7e, 14e · segment 500K€–3M€

---

## 6. ASSETS PRODUITS

| Fichier | Type | Statut |
|---------|------|--------|
| index.html | HTML | ✅ |
| vendre.html | HTML | ✅ |
| acheter.html | HTML | ✅ |
| le-journal.html | HTML | ✅ |
| a-propos.html | HTML | ✅ |
| contact.html | HTML | ✅ |
| conception.html | HTML | ✅ |
| style.css | CSS | ✅ |
| mentions-legales.html | HTML | ✅ |
| confidentialite.html | HTML | ✅ |
| cookies.html | HTML | ✅ |
| honoraires.html | HTML | ✅ |
| caroline.png | Image N&B | ✅ |
| logo_greenpartners.png | Image sans fond | ✅ |
| guide-deploiement.md | Markdown | ✅ |
| synthese-projet.md | Markdown | ✅ |

---

## 7. INSTRUCTIONS POUR NOUVELLE SESSION

Colle ce fichier en début de conversation avec ce message :

> *"Voici la synthèse complète du projet The Interior by Caroline. Reprends exactement là où on en est, sans repartir de zéro. Le site est en ligne sur theinteriorbycaroline.fr."*

Claude reconstituera l'état complet du projet immédiatement.

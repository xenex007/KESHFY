# 📘 KESHFY · كشف النقاط الذكي

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

> **كشفي** (KESHFY) - "Mon bulletin" - Le bulletin de notes prévisionnel intelligent pour le cycle moyen algérien.

## 📖 À propos

**كشفي (KESHFY)** est une application web monopage (SPA) conçue pour simuler et gérer les bulletins de notes des élèves du cycle moyen en Algérie. Elle suit rigoureusement les règles officielles de l'Éducation Nationale Algérienne et offre une interface moderne, intuitive et entièrement en arabe.

Le nom **"كشفي"** (KESHFY) signifie "Mon bulletin" en arabe, reflétant parfaitement la vocation de l'outil : un bulletin de notes personnel, intelligent et prévisionnel.

### ✨ Fonctionnalités principales

- 📊 **Gestion des trois trimestres** : Navigation fluide entre les périodes avec animations
- 📝 **Saisie intuitive** : Notes sur 20 pour le contrôle continu et sur 40 pour l'examen
- 🧮 **Calcul automatique** :
  - Moyenne du contrôle continu (selon les notes saisies)
  - Total sur 60 (contrôle + examen × 2)
  - Moyenne trimestrielle sur 20
  - Moyenne générale pondérée
- 🎯 **Indicateurs visuels** :
  - Badges de progression par trimestre
  - Points de statut (complet/partiel/vide)
  - Alertes visuelles pour les saisies invalides
- 🔄 **Flexibilité** :
  - Ajout dynamique de matières personnalisées
  - Modification des coefficients
  - Exemption individuelle des matières
- 💾 **Persistance** :
  - Sauvegarde automatique dans le navigateur (localStorage)
  - Export/Import JSON
  - Génération de PDF (via html2pdf.js)
- 🖨️ **Optimisation impression** : Mise en page A4 professionnelle

## 🚀 Démo en ligne

🔗 [Voir la démo](https://votre-username.github.io/keshfy)

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Design moderne avec variables CSS
- **JavaScript (ES6)** - Logique métier et interactivité
- **Google Fonts (Cairo)** - Typographie arabe élégante
- **html2pdf.js** - Génération de PDF

## 📦 Installation

### Prérequis

- Un navigateur web moderne (Chrome, Firefox, Edge, Safari)

### Méthode 1 - Simple (Cloner le dépôt)

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/keshfy.git

# Ouvrir le fichier dans le navigateur
cd keshfy
open index.html  # ou double-cliquez sur le fichier
Méthode 2 - Via GitHub Pages
Forker le dépôt

Activer GitHub Pages dans les paramètres

Accéder à https://votre-username.github.io/keshfy

📂 Structure du projet
text
keshfy/
├── index.html          # Fichier principal (HTML + CSS + JS intégrés)
├── README.md           # Documentation
├── LICENSE             # Licence MIT
└── assets/             # (optionnel) Images et ressources
🎯 Utilisation
1. Saisie des notes
Champ	Description	Plage
تقويم	Note d'évaluation continue	0-20
الفرض 1	Devoir surveillé n°1	0-20
الفرض 2	Devoir surveillé n°2 (optionnel)	0-20
الإختبار /40	Note d'examen (saisie sur 40)	0-40
2. Navigation
Cliquez sur les onglets pour basculer entre les trimestres

Les badges indiquent le nombre de matières évaluées

Les points de progression montrent l'état général

3. Gestion des matières
Ajouter : Utilisez le formulaire en bas du tableau

Modifier le coefficient : Ajustez le champ "المعامل"

Réinitialiser : Utilisez le bouton 🗑️ par ligne ou le bouton global

4. Export et sauvegarde
💾 حفظ : Sauvegarde en JSON (téléchargement)

📂 استيراد : Charge un fichier JSON sauvegardé

🖨️ طباعة : Impression optimisée

📥 PDF : Génère un PDF professionnel

🧮 Formules de calcul officielles
1. Moyenne du contrôle continu
text
معدل التقويم = (تقويم + فرض1 + فرض2) / Nombre de notes saisies
2. Total de la matière
text
المجموع /60 = معدل التقويم + (الإختبار × 2)
3. Moyenne trimestrielle
text
المعدل الفصلي /20 = المجموع / 3
4. Moyenne générale
text
المعدل الفصلي العام = Σ(معدل المادة × المعامل) / Σ(المعاملات النشطة)
5. Cas particuliers
Examen seul : Total = NoteExamen × 1.5 (projection sur 60)

Contrôle seul : Moyenne = معدل التقويم (provisoire)

Exemption : La matière est complètement exclue des calculs

📱 Compatibilité
Navigateur	Support
Chrome 60+	✅
Firefox 55+	✅
Safari 12+	✅
Edge 79+	✅
Opera 47+	✅
🤝 Contribution
Les contributions sont les bienvenues ! Voici comment contribuer :

Fork le projet

Créer une branche (git checkout -b feature/amazing-feature)

Commit vos changements (git commit -m 'Ajout d'une nouvelle fonctionnalité')

Push vers la branche (git push origin feature/amazing-feature)

Ouvrir une Pull Request

Directives de contribution
Respecter le style de code existant

Maintenir la compatibilité RTL

Tester sur plusieurs navigateurs

Mettre à jour la documentation si nécessaire

📄 Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.

🙏 Remerciements
Éducation Nationale Algérienne pour les règles officielles

La communauté open-source pour les bibliothèques utilisées

Google Fonts pour la police Cairo

📧 Contact
Auteur : [Votre Nom]

Email : [votre.email@example.com]

GitHub : @votre-username

🌟 Si ce projet vous a été utile, n'oubliez pas de laisser une ⭐ !
كشفي · بناء رصيدك الدراسي بذكاء

text

---

## 📋 Version simplifiée (README court)

```markdown
# 📘 KESHFY · كشف النقاط الذكي

> **كشفي** - Bulletin de notes prévisionnel intelligent pour le cycle moyen algérien.

## ✨ Fonctionnalités

- 📊 3 trimestres avec navigation animée
- 🧮 Calcul automatique selon les règles officielles
- ➕ Ajout de matières personnalisées
- 💾 Export/Import JSON et PDF
- 💿 Sauvegarde automatique
- 🎨 Interface RTL moderne

## 🚀 Utilisation

Ouvrez `index.html` dans votre navigateur.

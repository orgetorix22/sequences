# 📚 Séquences Pédagogiques - Lycée Younoussa Bamana

## Système de gestion des séquences d'anglais

Ce dépôt contient l'ensemble des séquences pédagogiques d'anglais pour le Lycée Younoussa Bamana, organisées selon une **structure standardisée** pour faciliter la création, le partage et la réutilisation des ressources.

---

## 🎯 Objectifs du système

1. **Cohérence** : Toutes les séquences suivent la même organisation
2. **Qualité** : Documentation complète (enseignant + élèves)
3. **Réutilisabilité** : Templates prêts à l'emploi
4. **Évolutivité** : Archivage des versions et amélioration continue
5. **Partage** : Faciliter la collaboration entre enseignants

---

## 📂 Structure du dépôt

```
sequences/
├── README.md (ce fichier)
├── STRUCTURE_MODELE_SEQUENCES.md (documentation complète du système)
│
├── _TEMPLATES/
│   ├── README_template.md
│   └── FICHE_SEQUENCE_ENSEIGNANT_template.md
│
└── 21._Premières_générales/
    ├── 203.AI/ ✅ (Séquence modèle complète)
    ├── 204._New_zealand/
    ├── 205._Happiness_in_the_workplace/
    └── ...
```

---

## ✅ Séquence modèle : 203.AI

La séquence **AI & Society** sert de **modèle de référence** pour toutes les futures séquences.

### Ce qu'elle contient

- ✅ **Fiche séquence enseignant complète** (10 séances détaillées)
- ✅ **Livret élève de 12 pages** (prêt à imprimer)
- ✅ **Structure de dossier standardisée**
- ✅ **README explicatif**
- ✅ **Évaluations avec grilles**
- ✅ **Ressources complémentaires**

### Structure de la séquence

```
203.AI/
├── README.md
├── 00_Documents_Generaux/
│   ├── AI_S00_LIVRET_Sequence.pdf
│   ├── FICHE_SEQUENCE_ENSEIGNANT.md ⭐
│   └── AI_S00_Progression_sequence.odt
├── 01_Seances/
├── 02_Evaluations/
├── 03_Corrections/
├── 04_Ressources_Complementaires/
├── 05_Differenciation/
├── 06_Sources/
└── 07_Archives/
```

👉 **Consultez** `21._Premières_générales/203.AI/README.md` pour voir la séquence complète

---

## 🚀 Créer une nouvelle séquence

### Méthode rapide

1. **Copier la structure**
   ```bash
   cp -r _TEMPLATES/structure_vide/ "21._Premières_générales/XXX.Nouveau_Theme/"
   ```

2. **Copier les templates**
   ```bash
   cp _TEMPLATES/README_template.md "21._Premières_générales/XXX.Nouveau_Theme/README.md"
   cp _TEMPLATES/FICHE_SEQUENCE_ENSEIGNANT_template.md "21._Premières_générales/XXX.Nouveau_Theme/00_Documents_Generaux/FICHE_SEQUENCE_ENSEIGNANT.md"
   ```

3. **Remplir les templates**
   - Compléter le README avec les infos de base
   - Développer la fiche séquence enseignant
   - Créer les documents élèves
   - Assembler le livret élève

4. **Vérifier la checklist** (voir `STRUCTURE_MODELE_SEQUENCES.md`)

### Workflow complet

Consultez le document **`STRUCTURE_MODELE_SEQUENCES.md`** pour :
- Le workflow détaillé de création
- La nomenclature des fichiers
- Les bonnes pratiques
- La checklist de validation

---

## 📋 Nomenclature des fichiers

### Format standard
```
[CODE]_[TYPE][NUMERO]_[TITRE].[extension]
```

### Exemples
- `AI_S01_What_is_AI.pdf` - Séance 1
- `AI_EVAL_CE_Teacher_Bans_AI.pdf` - Évaluation CE
- `NZ_S03_Maori_Culture_WS.pdf` - Worksheet séance 3

### Codes types
- `S01-S99` : Séances
- `EVAL_CE` : Évaluation Compréhension Écrite
- `EVAL_CO` : Évaluation Compréhension Orale
- `EVAL_EE` : Évaluation Expression Écrite
- `EVAL_EO` : Évaluation Expression Orale
- `WS` : Worksheet
- `CORR` : Correction

---

## 📚 Documents obligatoires par séquence

Pour chaque séquence, vous devez créer :

### 1. README.md
Présentation rapide (1 page) avec :
- Problématique
- Objectifs principaux
- Liste des séances
- Évaluations

### 2. FICHE_SEQUENCE_ENSEIGNANT.md
Document pédagogique complet (10-15 pages) avec :
- Progression détaillée séance par séance
- Objectifs CECRL
- Déroulements précis
- Différenciation
- Grilles d'évaluation

### 3. LIVRET_Sequence.pdf
Document élève imprimable avec :
- Toutes les activités
- Espaces pour répondre
- Vocabulaire
- Consignes tâche finale

### 4. Évaluations
- Au moins 1 évaluation sommative
- Correction complète
- Grille d'évaluation

---

## 🎨 Niveaux de classes

```
21._Premières_générales/
22._Terminales_générales/
23._Premières_STMG/
24._Terminales_STMG/
... etc.
```

---

## 📊 État d'avancement des séquences

### Premières Générales

| Code | Thème | État | Fichiers |
|------|-------|------|----------|
| 203.AI | AI & Society | ✅ **Complet** | README, Fiche, Livret, Évals |
| 204.NZ | New Zealand | 🟡 En cours | Documents bruts disponibles |
| 205.HWP | Happiness in the Workplace | 🟡 En cours | Documents bruts disponibles |

**Légende** :
- ✅ Complet : Structure standardisée + tous les documents
- 🟡 En cours : Documents disponibles mais non standardisés
- ⚪ À faire : Séquence à créer

---

## 🔧 Outils et ressources

### Documentation
- 📘 **`STRUCTURE_MODELE_SEQUENCES.md`** - Guide complet du système
- 📗 **`_TEMPLATES/README_template.md`** - Template de README
- 📙 **`_TEMPLATES/FICHE_SEQUENCE_ENSEIGNANT_template.md`** - Template de fiche

### Exemples
- 🌟 **`21._Premières_générales/203.AI/`** - Séquence modèle complète

### Logiciels recommandés
- **LibreOffice** : Édition de documents (.odt)
- **LaTeX** : Création d'évaluations professionnelles
- **Markdown** : Documentation enseignant
- **Git** : Gestion de versions

---

## 💡 Bonnes pratiques

### À faire ✅
- Suivre la structure standardisée
- Créer une fiche séquence détaillée
- Fournir toutes les corrections
- Prévoir de la différenciation
- Archiver les anciennes versions
- Tester avec les élèves avant de finaliser

### À éviter ❌
- Créer une structure différente
- Oublier la documentation enseignant
- Négliger les corrections
- Ignorer la différenciation
- Supprimer les anciennes versions sans archivage

---

## 🤝 Contribution

### Pour ajouter/modifier une séquence

1. **Créer une branche**
   ```bash
   git checkout -b nouvelle-sequence-xxx
   ```

2. **Suivre la structure standardisée**
   - Utiliser les templates
   - Respecter la nomenclature
   - Compléter tous les documents obligatoires

3. **Valider avec la checklist**
   (voir `STRUCTURE_MODELE_SEQUENCES.md`)

4. **Commit et push**
   ```bash
   git add .
   git commit -m "Ajout séquence XXX - [Description]"
   git push -u origin nouvelle-sequence-xxx
   ```

---

## 📞 Support

### Questions sur le système
- Consulter `STRUCTURE_MODELE_SEQUENCES.md`
- Regarder la séquence modèle `203.AI`
- Contacter l'équipe d'anglais

### Problèmes techniques
- Vérifier que Git est à jour
- S'assurer que les fichiers respectent la nomenclature
- Consulter les logs Git en cas d'erreur

---

## 📈 Feuille de route

### Court terme
- [ ] Standardiser la séquence 204.New_Zealand
- [ ] Standardiser la séquence 205.Happiness_in_the_Workplace
- [ ] Créer les corrections manquantes pour 203.AI

### Moyen terme
- [ ] Ajouter des documents de différenciation
- [ ] Créer des évaluations supplémentaires
- [ ] Développer des ressources audio/vidéo

### Long terme
- [ ] Standardiser toutes les séquences existantes
- [ ] Créer un site web pour consultation facile
- [ ] Partager avec d'autres établissements

---

## 📜 Licence et crédits

### Auteurs
- Mr Pierres - Lycée Younoussa Bamana
- [Autres contributeurs]

### Crédits
Les documents utilisent des sources authentiques :
- Articles de presse (avec adaptations pédagogiques)
- Vidéos éducatives
- Ressources libres de droits

Les sources sont documentées dans le dossier `06_Sources/` de chaque séquence.

### Utilisation
Ce système est conçu pour un usage pédagogique au sein de l'Éducation Nationale. Les documents peuvent être partagés entre enseignants et adaptés selon les besoins.

---

## 📅 Historique

### Version 1.0 (12 novembre 2025)
- ✅ Création du système de structure standardisée
- ✅ Finalisation de la séquence modèle 203.AI
- ✅ Création des templates réutilisables
- ✅ Documentation complète

---

## 🎯 Vision

Ce système vise à :
1. **Professionnaliser** la création de séquences pédagogiques
2. **Faciliter** le partage entre collègues
3. **Améliorer** la qualité de l'enseignement
4. **Gagner du temps** grâce à la réutilisation
5. **Pérenniser** les ressources créées

---

**Dernière mise à jour** : 12 novembre 2025
**Version du système** : 1.0

---

*"Une bonne structure libère la créativité pédagogique."*

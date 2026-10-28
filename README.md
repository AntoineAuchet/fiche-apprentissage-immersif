# 🧠 Fiche — Apprentissage multimédia & environnements immersifs

<p align="center">
  <img src="https://github.com/user-attachments/assets/1f81e900-e5e2-4057-bdbd-725089b707e3" alt="Fiche Apprentissage Immersif — Introduction" width="850">
</p>
<p align="center"><em>Capture d'écran : introduction de la fiche d'apprentissage immersif</em></p>

[![Site en ligne](https://img.shields.io/badge/site-en%20ligne-2ea44f?logo=githubpages&logoColor=white)](https://antoineau.github.io/fiche-apprentissage-immersif/)
![HTML5](https://img.shields.io/badge/HTML5-vanilla-%23E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-vanilla-%231572B6?logo=css3&logoColor=white)
![Dépendances](https://img.shields.io/badge/d%C3%A9pendances-0-success)
![Accessibilité](https://img.shields.io/badge/accessibilit%C3%A9-WCAG%202.1%20AA-blue)
![Licence](https://img.shields.io/badge/licence-CC%20BY%204.0-informational)

**Fiche de synthèse interactive** reliant la théorie de l'apprentissage multimédia (**CTML**, Mayer), la
théorie de la **charge cognitive** (Sweller) et le modèle **CAMIL** (Makransky & Petersen), jusqu'à la tension centrale
*présence vs charge cognitive* et aux biais qui la masquent.

Conçue et développée par un **UX Researcher en ergonomie cognitive**, cette fiche traduit un corpus de
recherche en un outil opérationnel : elle sert à la fois de synthèse de référence pour la conception
et l'évaluation de dispositifs d'apprentissage immersifs (VR/XR, jumeaux numériques, EdTech), et de
démonstration de compétences en vulgarisation scientifique et en développement front-end accessible.

➡️ **Version en ligne :** <https://antoineau.github.io/fiche-apprentissage-immersif/>

---

## 📑 Sommaire

1. [Contexte & objectifs](#-contexte--objectifs)
2. [Cadre théorique](#-cadre-théorique)
3. [Contenu de la fiche](#-contenu-de-la-fiche)
4. [Le simulateur immersion × conception](#-le-simulateur-immersion--conception)
5. [Accessibilité & qualité de lecture](#-accessibilité--qualité-de-lecture)
6. [Stack technique & structure du dépôt](#-stack-technique--structure-du-dépôt)
7. [Exécution locale & déploiement](#-exécution-locale--déploiement)
8. [Références](#-références)
9. [Citer ce travail](#-citer-ce-travail)
10. [English summary](#-english-summary) · [Licence](#-licence) · [Auteur](#-auteur)

## 🎯 Contexte & objectifs

L'évaluation de dispositifs d'apprentissage immersifs mobilise plusieurs cadres théoriques qui sont
rarement présentés ensemble : comment la théorie de la charge cognitive (Sweller) permet-elle
d'expliquer qu'un environnement plus immersif ne produit pas mécaniquement plus d'apprentissage ?
À quelles conditions la **présence** — sentiment d'être dans l'environnement virtuel — contribue-t-elle
réellement à l'apprentissage ?

Cette fiche répond à trois objectifs :

1. **Structurer** les grands modèles de l'apprentissage multimédia et immersif en une vue d'ensemble cohérente ;
2. **Vulgariser** chaque concept avec son mécanisme, un exemple concret et sa source ;
3. **Opérationnaliser** ces modèles via un simulateur interactif qui met en évidence la tension
   présence / charge cognitive — clef des arbitrages de conception en XR pédagogique.

**Publics visés :** concepteurs et ingénieurs pédagogiques, équipes produit XR/VR (jumeaux numériques,
EdTech), évaluateurs UX et ergonomes, étudiants et formateurs en sciences de l'apprentissage.

## 📐 Cadre théorique

| Modèle / théorie | Auteur(s) | Traité dans la fiche |
| --- | --- | --- |
| Cognitive Theory of Multimedia Learning (CTML) | R. E. Mayer | 3 hypothèses (double canal, capacité limitée, traitement actif) et 12 principes de conception, regroupés par fonction cognitive |
| Théorie de la charge cognitive | J. Sweller | Triade charge intrinsèque / extrinsèque / germane |
| Cognitive Affective Model of Immersive Learning (CAMIL) | G. Makransky & G. B. L. Petersen | Médias, contrôle, immersion, présence, charge et facteurs affectifs dans les environnements immersifs |
| Système 1 / Système 2 | D. Kahneman | Processus cognitifs rapides vs délibérés sollicités par les interfaces |
| Taxonomie de Bloom (révision Anderson & Krathwohl) | L. W. Anderson & D. R. Krathwohl | Niveaux d'objectifs pédagogiques visés |
| Biais cognitifs | — | Biais qui masquent la relation présence / apprentissage (effet « wow », effet de nouveauté…) |

## ✨ Contenu de la fiche

La fiche est organisée en un parcours, des fondations théoriques jusqu'à l'arbitrage de conception :

- **Fondations — CTML (Mayer)** : les 3 hypothèses et les 12 principes, regroupés par fonction
  cognitive, en cartes dépliables avec mécanisme, exemple concret et source ;
- **Charge cognitive (Sweller)** : triade intrinsèque / extrinsèque / germane, complétée par
  Système 1 / Système 2 (Kahneman) et la taxonomie de Bloom (révision Anderson & Krathwohl) ;
- **Immersion — CAMIL (Makransky & Petersen)** : médias, contrôle, immersion, présence, charge
  et facteurs affectifs dans les environnements immersifs ;
- **Synthèse** : la tension présence / charge cognitive, les biais qui la masquent, et le simulateur interactif.

## 🎛️ Le simulateur immersion × conception

Au cœur de la fiche, un **simulateur interactif** met en mouvement la relation non linéaire entre
immersion et apprentissage :

- **Deux curseurs** : *niveau d'immersion* (écran → VR immersive) × *qualité de conception pédagogique*
  (application des principes de Mayer) ;
- **En sortie** : la répartition de la charge cognitive, le niveau de présence ressenti et un
  **verdict d'adéquation pédagogique** ;
- **Leçon clé** : une forte immersion sans conception pédagogique solide augmente la charge
  extrinsèque et masque l'absence d'apprentissage derrière l'effet « wow » — un argument direct
  en faveur d'une évaluation outillée plutôt que de la seule impression des utilisateurs.

## ♿ Accessibilité & qualité de lecture

Conçue selon une démarche d'ergonomie cognitive appliquée à la lecture à l'écran :

- Contrastes conformes **WCAG 2.1 AA**, thème clair / sombre ;
- Respect de `prefers-reduced-motion` : aucune animation superflue ;
- Navigation **clavier** complète et rôles **ARIA** sur les curseurs et cartes dépliables.

## 🛠️ Stack technique & structure du dépôt

- **Fichier HTML autonome** : HTML/CSS/JS vanilla, aucune dépendance externe, aucun build ;
- **Hébergement automatique** via GitHub Pages (workflow GitHub Actions inclus).

### Structure du dépôt

```text
.
├── .github/
│   └── workflows/
│       └── pages.yml    # Déploiement automatique sur GitHub Pages
├── index.html           # La fiche complète — HTML/CSS/JS autonome
├── CITATION.cff         # Métadonnées de citation (bouton « Cite this repository »)
├── LICENSE              # Texte complet de la licence CC BY 4.0
└── README.md
```

### Exécution locale

Aucune installation : télécharger `index.html` et l'ouvrir dans un navigateur, ou cloner le dépôt :

```bash
git clone https://github.com/AntoineAu/fiche-apprentissage-immersif.git
open index.html   # macOS — ou double-clic dans un explorateur de fichiers
```

### Déployer sa propre copie

1. **Forkez** le dépôt ;
2. Dans **Settings → Pages**, choisissez **GitHub Actions** comme source ;
3. Le workflow inclus (`.github/workflows/pages.yml`) déploie la fiche automatiquement à chaque
   push sur `main`.

## 📚 Références

- Mayer, R. E. (2021). *Multimedia Learning* (3ᵉ éd.). Cambridge University Press.
- Mayer, R. E. (2005). Cognitive theory of multimedia learning. In R. E. Mayer (dir.), *The Cambridge Handbook of Multimedia Learning*. Cambridge University Press.
- Sweller, J., Ayres, P., & Kalyuga, S. (2011). *Cognitive Load Theory*. Springer.
- Makransky, G., & Petersen, G. B. L. (2021). The Cognitive Affective Model of Immersive Learning (CAMIL): A theoretical research-based model of learning in immersive virtual reality. *Educational Psychology Review*, 33(3), 937–958. [https://doi.org/10.1007/s10648-020-09586-2](https://doi.org/10.1007/s10648-020-09586-2)
- Kahneman, D. (2011). *Thinking, Fast and Slow*. Farrar, Straus and Giroux.
- Anderson, L. W., & Krathwohl, D. R. (dir.) (2001). *A Taxonomy for Learning, Teaching, and Assessing: A Revision of Bloom's Taxonomy of Educational Objectives*. Longman.

## 📜 Citer ce travail

Le bouton **« Cite this repository »** de la page du dépôt génère une citation (APA ou BibTeX) à partir
des métadonnées du fichier [`CITATION.cff`](CITATION.cff). En BibTeX :

```bibtex
@misc{auchet2026fiche,
  author       = {Auchet, Antoine},
  title        = {Fiche — Apprentissage multimédia et environnements immersifs},
  year         = {2026},
  howpublished = {Fiche interactive en ligne},
  url          = {https://antoineau.github.io/fiche-apprentissage-immersif/},
  note         = {Code : https://github.com/AntoineAu/fiche-apprentissage-immersif — licence CC BY 4.0}
}
```

## 🌍 English summary

An interactive summary sheet connecting Mayer's **Cognitive Theory of Multimedia Learning (CTML)**,
Sweller's **Cognitive Load Theory** and the **CAMIL** model (Makransky & Petersen), up to the central
*presence vs cognitive load* tension and the cognitive biases that mask it. Built as a single
dependency-free HTML file, designed for **WCAG 2.1 AA** accessibility (full keyboard navigation, ARIA
roles, reduced-motion support, light/dark themes) and deployed via GitHub Pages. An interactive
simulator explores how immersion and instructional design jointly shape cognitive load, presence and
learning outcomes. Live version: <https://antoineau.github.io/fiche-apprentissage-immersif/>.

## 📄 Licence

Contenu et code mis à disposition sous la licence
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.fr) —
voir le fichier [LICENSE](LICENSE) pour le texte complet. Vous êtes libre de réutiliser et d'adapter ce
travail, à condition d'en citer l'auteur.

## 👤 Auteur

**Antoine Auchet** — UX Researcher en ergonomie cognitive & IHM, spécialisé dans l'évaluation de
dispositifs d'apprentissage immersifs et numériques (VR/XR, jumeaux numériques, EdTech).

- 💼 [LinkedIn](https://www.linkedin.com/in/antoine-auchet/) · [Malt](https://www.malt.fr/profile/antoineauchet)
- 🧑‍💻 [GitHub](https://github.com/AntoineAu)
- 📫 antoine.auchet@proton.me

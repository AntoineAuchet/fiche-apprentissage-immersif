# 🧠 Fiche — Apprentissage multimédia & environnements immersifs

![HTML5](https://img.shields.io/badge/HTML5-plain-%23E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-plain-%231572B6?logo=css3&logoColor=white)
![No dependencies](https://img.shields.io/badge/dépendances-0-success)
![Accessibilité](https://img.shields.io/badge/accessibilit%C3%A9-WCAG%202.1%20AA-blue)

**Fiche de synthèse interactive** reliant la théorie de l'apprentissage multimédia (**CTML**, Mayer), la
théorie de la **charge cognitive** (Sweller) et le modèle **CAMIL** (Makransky), jusqu'à la tension centrale
*présence vs charge cognitive* et aux biais qui la masquent.

Conçue et développée par un **UX Researcher en ergonomie cognitive**, cette fiche traduit un corpus de
recherche en un outil opérationnel : elle sert à la fois de synthèse de référence pour la conception
et l'évaluation de dispositifs d'apprentissage immersifs (VR/XR, jumeaux numériques, EdTech), et de
démonstration de compétences en vulgarisation scientifique et en développement front-end accessible.

➡️ **Version en ligne :** <https://antoineau.github.io/fiche-apprentissage-immersif/>

<img width="945" height="478" alt="Fiche Apprentissage Immersif Intro" src="https://github.com/user-attachments/assets/1f81e900-e5e2-4057-bdbd-725089b707e3" />
Capture d'écran : Introduction de la fiche d'apprentissage immersif

---

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

## 📐 Cadre théorique

| Modèle / théorie | Auteur(s) | Traité dans la fiche |
| --- | --- | --- |
| Cognitive Theory of Multimedia Learning (CTML) | R. E. Mayer | 3 hypothèses (double canal, capacité limitée, traitement actif) et 12 principes de conception, regroupés par fonction cognitive |
| Théorie de la charge cognitive | J. Sweller | Triade charge intrinsèque / extrinsèque / germane |
| Cognitive Affective Model of Immersive Learning (CAMIL) | G. Makransky & G. B. Petersen | Médias, contrôle, immersion, présence, charge et facteurs affectifs dans les environnements immersifs |
| Système 1 / Système 2 | D. Kahneman | Processus cognitifs rapides vs délibérés sollicités par les interfaces |
| Taxonomie de Bloom (révision Anderson & Krathwohl) | L. W. Anderson & D. R. Krathwohl | Niveaux d'objectifs pédagogiques visés |
| Biais cognitifs | — | Biais qui masquent la relation présence / apprentissage (effet « wow », etc.) |

## ✨ Contenu

- **Les 3 hypothèses de la CTML** : cartes dépliables avec mécanisme, exemple, source et liens vers les principes associés.
- **Les 12 principes de Mayer**, regroupés par fonction cognitive (cartes dépliables).
- **Triade de charge cognitive**, Système 1 / Système 2 (Kahneman), taxonomie de Bloom.
- **Modèle CAMIL**, biais cognitifs, tension présence / charge.
- **Simulateur interactif** : deux curseurs (*immersion* × *qualité de conception*) pilotent la
  répartition de la charge cognitive et le niveau de présence, avec un verdict d'adéquation
  pédagogique — matérialisant la relation non linéaire entre immersion et apprentissage.

## ♿ Accessibilité & qualité de lecture

Conçue selon une démarche d'ergonomie cognitive appliquée à la lecture à l'écran :

- Contrastes conformes **WCAG 2.1 AA**, thème clair / sombre ;
- Respect de `prefers-reduced-motion` (aucune animation superflue) ;
- Navigation **clavier** complète et rôles **ARIA** sur les curseurs et cartes dépliables.

## 🛠️ Stack technique

- **Fichier HTML autonome** : HTML/CSS/JS vanilla, aucune dépendance externe, aucun build ;
- Hébergement automatique via **GitHub Pages** (GitHub Actions).

### Exécution locale

Aucune installation : télécharger `index.html` et l'ouvrir dans un navigateur, ou cloner le dépôt :

```bash
git clone https://github.com/AntoineAu/fiche-apprentissage-immersif.git
open index.html   # macOS — ou double-clic dans un explorateur de fichiers
```

## 📚 Références

- Mayer, R. E. (2021). *Multimedia Learning* (3ᵉ éd.). Cambridge University Press.
- Mayer, R. E. (2005). Cognitive theory of multimedia learning. In R. E. Mayer (dir.), *The Cambridge Handbook of Multimedia Learning*. Cambridge University Press.
- Sweller, J., Ayres, P., & Kalyuga, S. (2011). *Cognitive Load Theory*. Springer.
- Makransky, G., & Petersen, G. B. (2021). The Cognitive Affective Model of Immersive Learning (CAMIL). *Educational Psychology Review*, 33(3), 937–958.
- Kahneman, D. (2011). *Thinking, Fast and Slow*. Farrar, Straus and Giroux.
- Anderson, L. W., & Krathwohl, D. R. (dir.) (2001). *A Taxonomy for Learning, Teaching, and Assessing: A Revision of Bloom's Taxonomy of Educational Objectives*. Longman.

## 👤 Auteur

**Antoine Auchet** — UX Researcher en ergonomie cognitive & IHM, spécialisé dans l'évaluation de
dispositifs d'apprentissage immersifs et numériques (VR/XR, jumeaux numériques, EdTech).

- 💼 [LinkedIn](https://www.linkedin.com/in/antoine-auchet/) · [Malt](https://www.malt.fr/profile/antoineauchet)
- 🧑‍💻 [GitHub](https://github.com/AntoineAu)
- 📫 antoine.auchet@proton.me

# Tricentis Demo Web Shop

**Transformer une application e-commerce legacy et peu documentée en un référentiel de test structuré, priorisé et traçable.**

[Application de démonstration](https://demowebshop.tricentis.com/)

---

## En bref

- **Reverse-engineering fonctionnel** d’une application sans spécifications initiales, avec formalisation d’une baseline de **28 exigences métier (BR)** et **62 exigences fonctionnelles (FR)**.
- **Périmètre fondé sur les risques**, centré sur les six domaines clés du parcours e-commerce : authentification et session (connexion et inscription), catalogue et produits, panier, codes promotionnels, tunnel de commande, confirmation et historique.
- **Gouvernance de conception des tests** : **63 cas de test** priorisés, avec scénarios **positifs (39)** et **négatifs (24)**, répartis par priorité : **P1 (39)**, **P2 (19)** et **P3 (5)**.
- **Traçabilité complète** : **100 % des 62 FR** sont reliées à au moins un cas de test dans la matrice.

## Livrables

Les livrables sont consultables en ligne (GitHub Pages), sans rien télécharger :

| Document | Rôle |
|---|---|
| [Stratégie de test](https://florent01-star.github.io/test-strategy/Strategie_de_test.html) | Cadre d’approche : périmètre, priorisation par les risques et principes de test fonctionnel et de non-régression. |
| [Requirements](https://florent01-star.github.io/test-strategy/Requirements.html) | Baseline reconstruite des exigences métier et fonctionnelles, organisée par domaine et priorité. |
| [Test Cases](https://florent01-star.github.io/test-strategy/Test_Cases.html) | Référentiel des 63 scénarios, avec type positif/négatif, priorité, exigences couvertes et objectif de test. |
| [Matrice de traçabilité](https://florent01-star.github.io/test-strategy/Matrice_Tracabilite.html) | Vue de couverture reliant exigences, cas de test et domaines ; permet de vérifier la couverture des 62 FR à 100 %. |

Les fichiers sources (Word et Excel) sont disponibles dans le dossier Docs du projet (à consulter en clonant le projet par exemple), ils sont cependant dans une version plus ancienne que les fichiers html associés.

## Note méthodologique

L’application étudiée est un **bac à sable public statique**, sans cycle actif de développement, de livraison ou de mise en production auquel rattacher une campagne. Dans ce contexte, un Test Manager ne produit pas de **Test Plan dynamique** ni d’**Execution Report** : le premier dépend d’une version, d’un calendrier et de changements concrets ; le second exige une exécution réelle, des résultats observés et des anomalies qualifiées. Les quatre livrables ci-dessus documentent donc le travail pertinent ici : le cadrage et la conception du patrimoine de test, sans présenter des résultats d’exécution fictifs.

---

*Les indicateurs de couverture décrivent la traçabilité exigences-tests, et non le succès d’une campagne d’exécution.*
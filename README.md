<div align="center">

# Florent — Portfolio QA
### QA Test Manager / Test Lead · Tricentis Demo Web Shop

**Transformer une application e-commerce legacy et peu documentée en un référentiel de test structuré, priorisé et traçable.**

[Application de démonstration](https://demowebshop.tricentis.com/)

</div>

---

## En bref

- **Reverse-engineering fonctionnel** d’une application sans spécifications initiales, avec formalisation d’une baseline de **27 exigences métier (BR)** et **57 exigences fonctionnelles (FR)**.
- **Périmètre fondé sur les risques**, centré sur les six domaines clés du parcours e-commerce : authentification et session, catalogue et produits, panier, codes promotionnels, tunnel de commande, confirmation et historique.
- **Gouvernance de conception des tests** : **52 cas de test** priorisés, avec scénarios **positifs (37)** et **négatifs (15)**.
- **Traçabilité complète** : **100 % des 57 FR** sont reliées à au moins un cas de test dans la matrice.

## Livrables

| Document | Rôle |
|---|---|
| [`Stratégie de test.docx`](Stratégie%20de%20test.docx) | Cadre d’approche : périmètre, priorisation par les risques et principes de test fonctionnel et de non-régression. Ouvrir le document pour consulter la stratégie détaillée. |
| [`Requirements.xlsx`](Requirements.xlsx) | Baseline reconstruite des exigences métier et fonctionnelles, organisée par domaine et priorité. |
| [`Test Cases.xlsx`](Test%20Cases.xlsx) | Référentiel des 52 scénarios, avec type positif/négatif, priorité, exigences couvertes et objectif de test. |
| [`Matrice_Tracabilite.xlsx`](Matrice_Tracabilite.xlsx) | Vue de couverture reliant exigences, cas de test et domaines ; permet de vérifier la couverture FR à 100 %. |

## Note méthodologique

L’application étudiée est un **bac à sable public statique**, sans cycle actif de développement, de livraison ou de mise en production auquel rattacher une campagne. Dans ce contexte, un Test Manager ne produit pas de **Test Plan dynamique** ni d’**Execution Report** : le premier dépend d’une version, d’un calendrier et de changements concrets ; le second exige une exécution réelle, des résultats observés et des anomalies qualifiées. Les quatre livrables ci-dessus documentent donc le travail pertinent ici : le cadrage et la conception du patrimoine de test, sans présenter des résultats d’exécution fictifs.

---

*Portfolio de conception QA sur une application de démonstration. Les indicateurs de couverture décrivent la traçabilité exigences-tests, et non le succès d’une campagne d’exécution.*

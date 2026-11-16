# Étude comparative : blockchain publique, blockchain permissionnée et bases de données classiques dans le secteur financier

**Auteur : Yassine Leghlam**  
**Formation : Master FinTech / Blockchain**  
**Université Cadi Ayyad – FSJES Marrakech**

## Introduction

La transformation numérique du secteur financier repose sur la capacité des institutions à enregistrer, traiter, sécuriser et partager des informations. Les banques, les établissements de paiement, les assurances et les autres acteurs financiers utilisent traditionnellement des bases de données centralisées pour gérer les comptes, les opérations et les relations avec leurs clients.

Depuis l'apparition de Bitcoin, la technologie blockchain a proposé une autre manière d'enregistrer les transactions : un registre partagé entre plusieurs participants et organisé en blocs liés par des mécanismes cryptographiques. Cette innovation a suscité un intérêt important dans la finance, notamment pour les paiements, le règlement-livraison, la traçabilité et le partage d'informations entre organisations.

Cependant, toutes les blockchains ne fonctionnent pas de la même manière. Certaines sont publiques et ouvertes à tous, tandis que d'autres limitent la participation à des acteurs autorisés. En parallèle, les bases de données classiques restent largement utilisées et peuvent être mieux adaptées à plusieurs besoins opérationnels.

**Problématique : Dans quelles situations une institution financière a-t-elle intérêt à utiliser une blockchain publique, une blockchain permissionnée ou une base de données classique ?**

Pour répondre à cette question, cette étude présente les trois solutions, compare leurs caractéristiques et examine leurs usages possibles dans le secteur financier.

## 1. Présentation des trois solutions

### 1.1. La blockchain publique

Une blockchain publique est un registre numérique accessible à un grand nombre de participants. Dans un réseau public permissionless, toute personne peut généralement consulter le registre, soumettre une transaction et participer au fonctionnement du réseau selon les règles du protocole. La validation repose sur un mécanisme de consensus qui permet aux participants de s'accorder sur l'état du registre.

Bitcoin constitue un exemple connu de blockchain publique. Les transactions sont regroupées dans des blocs qui sont reliés entre eux par des empreintes cryptographiques (hashes). Cette structure rend les modifications rétroactives difficiles à réaliser et permet de vérifier publiquement l'historique des opérations.

**Exemple financier :** Bitcoin permet le transfert de valeur entre utilisateurs sans qu'une banque soit nécessaire pour enregistrer chaque transfert dans un registre central unique.

**Limites :** la transparence du registre peut poser des questions de confidentialité. Les performances, les frais et les délais de confirmation dépendent du réseau et de son activité. L'utilisation d'une blockchain publique ne supprime pas non plus les risques liés aux portefeuilles, aux plateformes d'échange ou aux applications construites autour du réseau.

### 1.2. La blockchain permissionnée

Une blockchain permissionnée est un registre distribué dont les droits de participation sont réservés à des personnes ou organisations autorisées. Les participants peuvent être identifiés et leurs droits de lecture, de soumission ou de validation des transactions peuvent être définis selon les règles du réseau.

Hyperledger Fabric est un exemple de plateforme de registre distribué permissionné conçue pour les organisations. Elle permet à plusieurs entités de partager un registre tout en organisant les identités, les autorisations et les règles de validation.

**Exemple financier :** plusieurs banques pourraient utiliser un registre partagé pour suivre certaines étapes d'une opération entre elles, avec des droits d'accès définis pour chaque participant.

**Limites :** la gouvernance doit être clairement organisée entre les membres. Le système nécessite une coordination technique et juridique. En outre, le fait de limiter les participants peut réduire le degré de décentralisation par rapport à une blockchain publique.

### 1.3. La base de données classique

Une base de données classique est un système organisé de stockage et de gestion des informations. Dans un modèle centralisé, une organisation ou un administrateur contrôle généralement l'infrastructure, les droits d'accès et les opérations de mise à jour.

Les banques utilisent notamment des bases de données pour gérer les comptes, les clients, les paiements et les opérations internes. Ces systèmes peuvent offrir des performances élevées, des mécanismes avancés de contrôle d'accès et des outils de sauvegarde et de récupération.

**Exemple financier :** une banque peut enregistrer les soldes de ses clients et les mouvements de leurs comptes dans son propre système d'information.

**Limites :** lorsque plusieurs organisations doivent partager des informations, elles peuvent devoir synchroniser leurs systèmes et rapprocher leurs registres. La confiance repose alors largement sur les procédures, les contrôles et les accords entre les organisations.

## 2. Analyse comparative

| Critère | Blockchain publique | Blockchain permissionnée | Base de données classique |
|---|---|---|---|
| Accès | Généralement ouvert | Réservé aux membres autorisés | Défini par l'organisation |
| Identité | Souvent pseudonyme | Participants identifiés | Utilisateurs identifiés |
| Gouvernance | Règles du protocole et communauté | Organisation ou consortium | Administrateur / organisation |
| Validation | Consensus du réseau | Mécanisme défini par le réseau | Contrôle du système central |
| Transparence | Forte, selon le réseau | Contrôlée selon les droits | Limitée aux utilisateurs autorisés |
| Confidentialité | Peut être limitée | Peut être organisée par permissions | Généralement configurable |
| Performance | Dépend du réseau et du consensus | Peut être optimisée selon le réseau | Souvent élevée pour un usage interne |
| Cas d'usage | Transferts ouverts et vérifiables | Échanges entre organisations | Gestion interne des opérations |

Cette comparaison est générale. Les caractéristiques exactes varient selon la technologie, sa configuration et le contexte d'utilisation. En particulier, une blockchain publique n'est pas nécessairement totalement transparente dans toutes ses applications, et une blockchain permissionnée peut offrir différents niveaux de visibilité.

### 2.1. Gouvernance et contrôle

La principale différence concerne la manière dont les participants accèdent au système et prennent part à sa gestion. Dans une blockchain publique permissionless, l'accès au réseau est ouvert selon les règles du protocole. Dans une blockchain permissionnée, les participants sont admis et leurs rôles sont définis. Dans une base de données classique, l'organisation responsable contrôle généralement l'administration du système.

Pour une institution financière, ce critère est important car elle doit savoir qui peut consulter les données, initier une opération et participer à sa validation.

### 2.2. Transparence et confidentialité

La blockchain publique facilite la vérification des transactions enregistrées, mais cette visibilité peut être difficile à concilier avec les besoins de confidentialité des institutions financières. Les adresses utilisées sur un réseau public ne correspondent pas nécessairement directement à l'identité civile des utilisateurs, mais les transactions peuvent rester observables.

La blockchain permissionnée permet de limiter l'accès aux données en fonction des rôles et des autorisations. Une base de données classique permet également de gérer des accès restreints, sous le contrôle de l'organisation qui l'administre.

### 2.3. Performance et coûts

Une blockchain publique doit coordonner les participants du réseau selon son mécanisme de consensus. Les délais et les frais peuvent donc varier. Une blockchain permissionnée peut utiliser des mécanismes adaptés à un groupe connu de participants, ce qui peut améliorer certains aspects opérationnels.

Une base de données classique peut être plus simple et moins coûteuse à exploiter lorsqu'une seule organisation contrôle les opérations. Toutefois, dans un environnement où plusieurs institutions doivent partager un registre, les coûts de rapprochement et de coordination entre systèmes doivent également être pris en compte.

## 3. Applications possibles dans le secteur financier

### 3.1. Paiements et transferts de valeur

Une blockchain publique peut permettre des transferts de valeur entre utilisateurs sans dépendre d'un registre bancaire central unique. Elle peut être pertinente pour étudier les paiements ouverts, mais les questions de volatilité, de conformité, de frais et de protection des utilisateurs doivent être prises en compte.

### 3.2. Échanges entre institutions financières

Une blockchain permissionnée peut être étudiée pour le partage d'informations entre banques, assureurs ou autres institutions. Un registre commun peut améliorer la traçabilité des opérations et réduire certains rapprochements manuels, à condition que les participants s'accordent sur les règles de gouvernance et les données partagées.

### 3.3. Gestion interne et relation client

Pour les opérations internes d'une banque, une base de données classique peut rester la solution la plus adaptée. Elle permet de gérer les comptes clients, les opérations et les données confidentielles avec des outils déjà intégrés aux systèmes d'information de l'établissement.

## 4. Discussion : quelle solution choisir ?

Le choix dépend du problème à résoudre et du nombre d'acteurs impliqués.

- **Blockchain publique :** pertinente lorsque l'ouverture du réseau, la vérifiabilité et la possibilité de participer sans autorisation préalable sont recherchées.
- **Blockchain permissionnée :** pertinente lorsque plusieurs organisations identifiées doivent partager un registre, tout en conservant un contrôle sur les participants et les accès.
- **Base de données classique :** pertinente lorsque les données sont gérées principalement par une seule organisation et qu'un registre distribué n'apporte pas d'avantage suffisant.

Il faut également prendre en compte les exigences de protection des données, de cybersécurité, d'audit, de conformité réglementaire, de gouvernance et de continuité d'activité. Une blockchain ne garantit pas automatiquement la qualité des données saisies ni l'absence de fraude. Les procédures de contrôle restent donc indispensables.

## Conclusion

Cette étude montre que la blockchain publique, la blockchain permissionnée et la base de données classique répondent à des besoins différents dans le secteur financier.

La blockchain publique favorise l'ouverture et la vérification collective des transactions. La blockchain permissionnée permet à plusieurs organisations identifiées de partager un registre avec des règles d'accès contrôlées. La base de données classique demeure une solution efficace pour les traitements internes et les situations où une organisation conserve la maîtrise des données.

Ainsi, il n'existe pas une technologie meilleure dans tous les cas. La décision doit être fondée sur les objectifs de l'institution financière, les besoins de partage, le niveau de confidentialité, les coûts, la performance et les obligations réglementaires.

## Références bibliographiques

Les références détaillées et les liens de consultation sont présentés dans le fichier [`sources.md`](sources.md).

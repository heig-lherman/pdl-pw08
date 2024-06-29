# Processus de développement
Il convient de suivre un modèle itératif et incrémentiel qui s'adapte bien aux exigences complexes et aux besoins d'évolution constante typiques des projets technologiques avancés comme celui-ci. 

## Étapes clés
Voici les étapes clés de ce processus :

### 1. Planification du projet
- **Définition des objectifs** : Clarifier et affiner les objectifs du projet en fonction du cahier des charges.
- **Planification des ressources** : Estimer et allouer les ressources nécessaires, incluant le personnel, les outils de développement, et les composants matériels.
- **Établissement d'un calendrier** : Créer un calendrier de projet détaillé avec des jalons clés et des échéances pour le développement, les tests, et le déploiement.

### 2. Analyse des besoins
- **Collecte des exigences** : Déterminer les besoins précis des utilisateurs finaux et des autres parties prenantes en conduisant des interviews, des enquêtes, et des sessions de brainstorming.
- **Spécification des exigences** : Documenter les exigences fonctionnelles et non fonctionnelles de façon détaillée pour chaque composante du système.
- **Validation des exigences** : S'assurer que les exigences sont réalisables, testables, et alignées avec les objectifs du projet.

### 3. Conception du système
- **Architecture du système** : Développer un schéma d'architecture détaillé qui inclut le matériel, le logiciel, les réseaux, et les interfaces.
- **Conception détaillée** : Spécifier la structure interne de chaque composant du système, y compris les schémas de circuits pour les dispositifs IoT et les détails de l'interface utilisateur pour la plateforme web.
- **Revue de conception** : Organiser des sessions de révision avec les parties prenantes pour valider les plans de conception.

### 4. Développement et implémentation
- **Programmation du logiciel** : Écrire le code pour les composants logiciels du dispositif et de la plateforme en suivant les meilleures pratiques de développement sécurisé.
- **Fabrication du prototype** : Assembler le prototype du dispositif en utilisant les composants sélectionnés.
- **Intégration** : Combiner le matériel et le logiciel pour créer une version complète du système à tester.

### 5. Test du système
- **Tests unitaires et d'intégration** : Vérifier chaque composant individuellement et ensemble pour s'assurer qu'ils fonctionnent comme prévu.
- **Test d'acceptation utilisateur** : Permettre aux utilisateurs finaux de tester le système dans des conditions réelles pour valider la fonctionnalité et l'ergonomie.
- **Résolution des problèmes** : Identifier et corriger les défauts et les problèmes de performance trouvés pendant les tests.

### 6. Déploiement
- **Installation sur site** : Installer et configurer le dispositif sur les véhicules cibles.
- **Formation des utilisateurs** : Former les utilisateurs finaux et les techniciens sur l'utilisation et la maintenance du système.
- **Lancement** : Mettre le système en opération et surveiller sa performance initial.

### 7. Maintenance et évolutions
- **Support technique** : Fournir un support continu pour résoudre les problèmes opérationnels et répondre aux questions des utilisateurs.
- **Mises à jour logicielles** : Développer et déployer des mises à jour pour améliorer la fonctionnalité, la sécurité, et la performance du système.
- **Évaluation et améliorations** : Réévaluer périodiquement le système pour identifier les opportunités d'amélioration et mettre en œuvre des améliorations.

## Pratiques agiles mises en oeuvres

L'intégration de pratiques agiles peut considérablement améliorer la réactivité de l'équipe aux changements, favoriser une meilleure collaboration entre les parties prenantes et augmenter la qualité globale du produit. 

L'adoption de ces pratiques agiles offrira à l'équipe de projet la flexibilité nécessaire pour s'adapter aux exigences en constante évolution et aux défis techniques tout en maintenant un rythme de développement soutenu et en maximisant la valeur du produit pour les utilisateurs finaux.

Voici trois pratiques agiles essentielles qui seraient particulièrement bénéfiques pour ce projet :

### 1. Développement itératif et incrémental
#### Justification :
Le développement itératif permet de diviser le projet en plusieurs cycles courts et gérables, appelés itérations. Chaque itération produit une version incrémentée du produit, offrant une opportunité régulière d'évaluer et d'ajuster le cap du projet en fonction des retours des utilisateurs et des nouvelles exigences. Cette méthode est particulièrement adaptée à la nature complexe et techniquement sophistiquée des systèmes IoT, où les exigences peuvent évoluer en fonction des découvertes faites lors du développement et des tests.

### 2. Revues régulières avec les parties prenantes
#### Justification :
Les revues régulières impliquent des réunions avec toutes les parties prenantes du projet, y compris les techniciens, les managers, et les utilisateurs finaux. Ces réunions servent à présenter les fonctionnalités développées lors de l'itération précédente et à recueillir des retours critiques. Ce dialogue continu aide à assurer que le produit final répondra vraiment aux besoins des utilisateurs et reste aligné avec les objectifs commerciaux et légaux du projet. Pour un dispositif IoT dans le domaine de la sécurité routière, il est essentiel que le produit final soit non seulement techniquement fiable, mais également intuitif et conforme aux réglementations de sécurité.

### 3. Intégration et déploiement continus (CI/CD)
#### Justification :
L'intégration continue (CI) et le déploiement continu (CD) sont des pratiques où les modifications de code sont intégrées, testées, et déployées fréquemment. Cette approche réduit les risques associés à la fusion de grandes modifications tard dans le cycle de vie du développement et améliore la qualité du produit en identifiant rapidement les défauts. Pour un projet IoT, où le système doit interagir harmonieusement entre les composants matériel et logiciel, CI/CD assure que chaque changement reste compatible et performant à travers toutes les parties du système, facilitant ainsi des déploiements fluides et sans interruption, même lorsque le système est déjà en opération.

## Personas
### Pierre, CEO d’une entreprise de logistique
- **Âge** : 52 ans
- **Rôle** : Dirige une grande entreprise de transport international avec un focus majeur sur les itinéraires traversant les Alpes suisses.
- **Objectifs** : Maximiser la sécurité de sa flotte tout en minimisant les incidents et les retards, réduire les coûts opérationnels liés aux accidents et améliorer systématiquement la satisfaction clientèle.
- **Attentes** : Attend du dispositif qu'il soit non seulement fiable et efficace dans la prévention des collisions, mais qu'il soit aussi facile à intégrer aux systèmes existants de l'entreprise sans perturber les opérations. Espère que l'utilisation de technologies avancées puisse également servir comme point de vente unique pour attirer de nouveaux clients soucieux de la sécurité.

### Chloé, Analyste de données
- **Âge** : 35 ans
- **Rôle** : Responsable de la gestion et de l'analyse des flux de données issues des divers équipements IoT déployés sur le terrain.
- **Objectifs** : Transformer les données en insights stratégiques qui peuvent directement influencer les politiques internes de sécurité et d'opération. Elle aspire également à développer des modèles prédictifs pour identifier les zones à haut risque avant qu'un accident se produise.
- **Attentes** : Nécessite des données exhaustives et de haute précision, ainsi que des outils d'analyse puissants sur la plateforme web pour effectuer des analyses temps réel et historiques. Elle souhaite que les données soient structurées de manière à faciliter leur intégration avec d'autres outils d'analyse.

### Julien, Ingénieur système
- **Âge** : 40 ans
- **Rôle** : A la charge de concevoir et de perfectionner les aspects techniques du dispositif, en veillant à leur intégrité et leur conformité aux normes industrielles.
- **Objectifs** : Créer un dispositif qui soit à la fois durable et fiable dans des conditions météorologiques et de trafic variées. Il vise également à minimiser la complexité de l'installation et de la maintenance.
- **Attentes** : Intégration des dernières avancées en matière de capteurs et de connectivité sans fil pour garantir la communication ininterrompue entre les composants du dispositif. Il attend des retours de la part des techniciens de terrain pour optimiser les futures versions du produit.

### Marc, Manager de l’Office des Routes (OFROU)
- **Âge** : 47 ans
- **Rôle** : Gestionnaire de la sécurité routière, il travaille avec de multiples agences pour améliorer la sécurité des routes nationales.
- **Objectifs** : Intégrer de manière efficace des solutions technologiques qui peuvent réduire significativement les accidents et améliorer la fluidité du trafic.
- **Attentes** : Une plateforme qui lui permet non seulement de consulter rapidement les données des incidents, mais aussi d'exploiter ces données pour planifier des améliorations infrastructurelles. Il cherche des outils prédictifs et des dashboards intuitifs pour simplifier la prise de décision.

### Émilie, Technicienne d’installation
- **Âge** : 30 ans
- **Rôle** : Travaille sur le terrain pour installer le dispositif sur une variété de véhicules dans différentes configurations.
- **Objectifs** : Effectuer des installations rapides, précises et sécurisées pour éviter les retours ou les pannes de matériel dues à une installation inadéquate.
- **Attentes** : Des manuels d'installation détaillés et des outils adaptés à différents modèles de véhicules, permettant une installation uniforme et simplifiée. Espère un support technique réactif en cas de problèmes.

### Thomas, Conducteur de poids lourd
- **Âge** : 45 ans
- **Rôle** : Conduit régulièrement sur des itinéraires longue distance à travers l'Europe, principalement sur des routes complexes et chargées.
- **Objectifs** : Maintenir un bilan de sécurité impeccable et éviter les retards liés aux conditions routières et aux manœuvres dangereuses.
- **Attentes** : Un système discret mais efficace qui lui fournit des alertes précises sans nécessiter une interaction constante ou distraire de la conduite. Préfère que les mises à jour du système soient automatiques et non intrusives.

### Sophie, Postière
- **Âge** : 28 ans
- **Rôle** : Elle gère des livraisons quotidiennes dans des zones urbaines et rurales, souvent dans des délais serrés.
- **Objectifs** : Optimiser les itinéraires pour garantir la livraison rapide du courrier, tout en assurant sa propre sécurité et celle des autres usagers de la route.
- **Attentes** : Un dispositif qui nécessite peu ou pas d'interaction de sa part et qui ne compromette pas ses performances de livraison. Elle souhaite une solution qui s'adapte facilement à son véhicule sans modifications majeures.
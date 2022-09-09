## Titre

Portail InnerSource

## Patette

Les contributeurs potentiels ne peuvent pas facilement découvrir les projets InnerSource qui les intéressent. En créant un site Web intranet qui indexe toutes les informations disponibles sur les projets InnerSource, vous permettez aux contributeurs d'en savoir plus sur les projets susceptibles de les intéresser et aux propriétaires de projets InnerSource d'attirer un public extérieur.

## Problème

Les équipes de projet d'InnerSource ont du mal à attirer des contributions extérieures.

Les projets InnerSource de votre organisation se multiplient, mais les contributeurs potentiels n'ont aucun moyen facile de les découvrir.

## Histoire

Vous essayez d'établir une pratique InnerSource au sein de votre organisation. Vous êtes au courant de certains projets exécutés à l'aide d'un modèle InnerSource, mais leur existence n'est communiquée que par le bouche à oreille, par e-mail ou par des conversations parallèles avec d'autres employés. En conséquence, les propriétaires de projets InnerSource ont du mal à attirer des contributeurs.

Il n'y a pas de ressource unique et partagée à laquelle les employés de toute l'organisation peuvent accéder, ce qui leur permettra de découvrir facilement tous les projets InnerSource en cours. Cela limite considérablement le potentiel de croissance de chaque projet InnerSource.

Que peut-on faire pour aider tous les projets InnerSource à accroître leur visibilité auprès d'un public aussi large que possible et à attirer des contributeurs à l'échelle de l'organisation ?

## Contexte

* Votre organisation souhaite adopter un style de travail InnerSource.
* Les propriétaires de projets InnerSource cherchent un moyen d'attirer le public vers leurs projets. Cependant, ils sont limités par les canaux de communication à leur disposition par lesquels ils pourraient faire de la publicité auprès de contributeurs potentiels.
* Les projets InnerSource de votre organisation se multiplient.
* Ce problème est aggravé par le fait que l'application de gestion de contrôle de source partagée utilisée a des capacités de recherche si limitées que même les développeurs à la recherche de projets InnerSource trouvent frustrant de les localiser.

## Conditions préalables

* Les managers ont tacitement accepté que leurs employés participent aux projets InnerSource
* Un système de gestion de contrôle de code source partagé est utilisé et fournit un accès par programme au contenu des référentiels qu'il héberge.
* Il existe un service au sein de votre organisation chargé de promouvoir la collaboration InnerSource

## Les forces

* Le plein potentiel des équipes d'ingénierie distinctes de s'associer à des défis communs n'est pas réalisé
* Il est difficile pour les particuliers de découvrir quels projets InnerSource existent
* Il est difficile pour les porteurs de projet InnerSource d'attirer un public de contributeurs externes

## Solutions

Créez un site Web intranet InnerSource Portal où les propriétaires de projets InnerSource peuvent facilement annoncer la disponibilité de leurs projets.

Les principales propriétés du portail sont :

* Les visiteurs du portail InnerSource devraient pouvoir voir tous les projets disponibles ainsi que rechercher des projets spécifiques en fonction de divers critères tels que le nom du projet, les technologies utilisées, les noms des contributeurs, l'unité commerciale de parrainage, etc.
* Les informations affichées via le portail InnerSource doivent être sous le contrôle total des propriétaires de projet InnerSource à tout moment. De préférence, en se procurant ces informations directement à partir d'un fichier de données spécifique ou de métadonnées stockées dans le référentiel du projet lui-même.
* Les propriétaires de projet doivent inclure toutes les informations pertinentes concernant leurs projets dans ces fichiers de données, y compris le nom du projet, les noms des contributeurs de confiance, une brève description et des liens vers le référentiel de code ou toute documentation complémentaire.
* (facultatif) Alors que la plupart des organisations choisissent de rendre leur portail uniquement disponible sur leur intranet, certaines organisations ont choisi de rendre leur portail disponible sur l'Internet public. Ce dernier peut être intéressant pour les organisations qui souhaitent afficher des informations supplémentaires sur leur approche InnerSource dans leur portail, par ex. à des fins d'image de marque et de recrutement.

Lors du lancement du portail, une campagne de communication promouvant l'ajout de fichiers de données ou de métadonnées InnerSource aux référentiels de code devrait être envisagée, afin de renforcer le nombre de projets affichés dans le portail.

Une [implémentation de référence](https://github.com/SAP/project-portal-for-innersource) d'un portail InnerSource est disponible sur GitHub et ouverte aux contributions. Il répertorie tous les projets InnerSource d'une organisation de manière interactive et facile à utiliser. Les projets peuvent s'auto-enregistrer à l'aide d'un sujet GitHub dédié et fournir des métadonnées supplémentaires.

![Example of an InnerSource Portal](../../assets/img/portal-overview.png "Example of an InnerSource Portal")

## Contexte résultant

* Le portail InnerSource a permis aux propriétaires de projets InnerSource d'annoncer leurs projets à un public à l'échelle de l'organisation. En raison de cette visibilité accrue, ils attirent des communautés de contributeurs beaucoup plus importantes que jamais auparavant.
* Pour ceux qui cherchent à s'impliquer dans des projets InnerSource, le portail InnerSource leur a permis de découvrir exactement le type d'opportunités qui les intéresse en effectuant une recherche simultanée dans tous les projets InnerSource disponibles en fonction de leurs critères spécifiques.
* La satisfaction des besoins de ces deux publics a contribué à établir InnerSource comme une option viable et attrayante pour tous les secteurs de l'organisation à tirer parti pour accomplir des choses ensemble qu'ils ne pourraient pas avoir séparément.

## instances connues

* **Une grande organisation de services financiers** a utilisé la création d'un portail InnerSource pour fournir un mécanisme de publicité et de découverte des projets InnerSource existants dans différentes unités commerciales
* **SAP** fait la promotion des projets InnerSource dans le portail InnerSource - les projets peuvent s'auto-enregistrer à l'aide des rubriques GitHub. Le [Repository Activity Score](repository-activity-score.md) définit l'ordre par défaut des projets InnerSource dans le portail. Voir également [Michael Graf & Harish B (SAP) at ISC.S11 - The Unexpected Path of Applying InnerSource Patterns](https://www.youtube.com/watch?v=6r9QOw9dcQo&list=PLCH-i0B0otNQZQt_QzGR9Il_kE4C6cQRy&index=6). Sa base de code est publiée en tant que [implémentation de référence](https://github.com/SAP/project-portal-for-innersource) et ouverte aux contributions.
* **Elbit Systems** a utilisé ce modèle et ajouté la gamification en plus.
  * [Gamification comme moyen de changement culturel et booster d'engagement InnerSource](https://www.oreilly.com/library/view/oscon-2018-/9781492026075/video321579.html) | Shelly Nizri | OSCON 2018 - Portland, Oregon
  * Des îles, des monstres et de la source intérieure [(diapositives)](https://docs.google.com/presentation/d/1P1OCEK9B6eSrVRUclVWY6meSI-qHOBjM_UAPNvCZamU/edit#slide=id.p15), [(vidéo)](https:// drive.google.com/file/d/1pM89uHMn0vhE3ayFJDGYcCO8R0tAXXZD/view?usp=drivesdk) | InnerSource Spring Summit 2019 (Galway, Irlande)
  * Le code réalisant cette plateforme a été open source et est disponible sur [gitlab.com/gilda2](https://gitlab.com/gilda2)
* **American Airlines** fait la promotion des projets InnerSource via un [place de marché interne InnerSource](https://tech.aa.com/2020-10-30-innersource/). Comme pour SAP, les projets s'auto-enregistrent en ajoutant "innersource" en tant que sujet GitHub. Les projets sont consultables et filtrables par langue, sujets, nombre de problèmes ouverts, etc.
* **Banco Santander** a créé un portail public appelé [Santander ONE Europe InnerSource Community](https://innersourceportal.santander.com/) pour soutenir et accroître l'adoption d'InnerSource. En plus du catalogue de projets, le portail comprend des contenus pertinents tels que la documentation, la méthode de travail, les actualités et les événements.

![Santander InnerSource Portal](../../assets/img/santander_portal.png "Banco Santander InnerSource Portal")

## Références

* Il a été prouvé que le modèle de portail InnerSource fonctionne extrêmement bien avec le modèle InnerSource [Gig Marketplace] (./gig-marketplace.md) associé dans ce contexte

## Statut

* Structuré

## Auteur(s)

* Stephen McCall

## Remerciements

* Shelly Nizri
* Melinda Malmgren
* Michel Graf
* Jesús Alonso Gutierrez

## Titre

Licence InnerSource

## Patette

Deux entités juridiques appartenant à la même organisation souhaitent partager le code source d'un logiciel mais s'inquiètent des implications en termes de responsabilité légale ou de comptabilité interentreprises.

Une **licence InnerSource** fournit un cadre juridique réutilisable pour le partage du code source au sein de l'organisation. Cela ouvre de nouvelles possibilités de collaboration et rend explicites les droits et obligations des entités juridiques impliquées.

## Problème

Lorsque deux entités juridiques ou plus au sein d'une organisation souhaitent partager du code entre elles, elles ont besoin d'un accord sur les conditions et souvent d'un contrat légal. La création de tels accords sur une base par projet demande des efforts et crée un obstacle au partage. c'est-à-dire qu'une équipe au sein d'une entité juridique peut décider de ne pas partager son code source avec une autre entité juridique de l'organisation car cela semble compliqué.

Les obstacles au partage peuvent entraîner des silos et une duplication des efforts dans la reconstruction de solutions similaires dans plusieurs parties de l'organisation.

Au moment du partage du code source, il est impossible de prédire de manière fiable quelle sera la valeur du partage. Si l'activité de partage nécessite un effort important (c'est-à-dire la négociation des conditions d'utilisation), les personnes morales sont moins susceptibles de le faire, car elles sont préoccupées par le retour sur investissement.

## Contexte

- Une grande organisation avec de nombreuses entités juridiques (filiales) qui souhaitent partager du code. Lorsque l'organisation s'agrandit, la valeur de ce modèle augmente.
- Selon la définition, les personnes morales ont leurs propres droits et obligations juridiques.
- Plusieurs de ces entités juridiques développent des logiciels et utilisent les services des autres entités juridiques. Ils ont une motivation pour contribuer au code source de l'autre.
- Une complexité suffisante de l'organisation et de sa structure organisationnelle

## Les forces

- **Niveau d'effort** requis pour rédiger des accords formels, en particulier s'ils doivent tenir compte des perspectives techniques, juridiques et commerciales.
- Une grande organisation (composée de nombreuses entités juridiques) a de nombreux **règlements internes**. Tout nouvel accord conclu doit se conformer à ces réglementations, par ex. sécurité, confidentialité, processus d'approvisionnement, etc. Le volume de réglementations peut rendre difficile l'évaluation de la conformité du partage de logiciels entre deux entités juridiques à ces réglementations, en particulier lorsqu'il n'existe pas de procédure standard.
- Si l'une des entités juridiques de l'organisation a un **modèle commercial** qui dépend d'un code propriétaire et de la comptabilisation des frais de licence au sein de l'organisation
- **Culture d'entreprise** qui n'est pas habituée à la collaboration InnerSource et au code de partage. Il en résulte une incertitude quant aux droits et obligations lors de l'utilisation du code partagé.
- La liberté d'utilisation du logiciel conduit à la concurrence et à la propagation de la propriété
- Il existe des contrats légaux en place qui couvrent le partage du code source. Ces contrats ne sont pas standardisés, ils créent donc un effort supplémentaire de négociation et de compréhension pour chaque projet. Les contrats existants peuvent également ne pas autoriser le partage du code source dans un sens suffisamment ouvert pour prendre en charge une véritable approche InnerSource.
- Alternativement, il n'y a pas de contrats légaux en place mais le code source est partagé de manière informelle. Cela pourrait créer une incertitude dans les cas où la clarté sur la propriété, les droits et les obligations est nécessaire.

## Solutions

Création d'une **licence InnerSource** adaptée aux besoins de l'organisation en question (et de ses entités juridiques). Cette licence doit être suffisamment générique pour s'appliquer aux relations interentreprises les plus importantes.

Il est important d'écrire la licence InnerSource de sorte qu'elle permette véritablement des collaborations de type OpenSource au-delà des frontières des entités juridiques impliquées. Les 4 libertés du logiciel libre doivent donc être intégrées dans la licence.

La licence est écrite comme un document juridique formel et peut être utilisée dans le cadre de contrats entre les entités juridiques pour régir les accords de partage de code.

## Contexte résultant

Avec la licence InnerSource, nous disposons d'un outil pour partager le code entre les entités juridiques au sein de notre organisation.

La licence simplifie les conversations au sein de notre organisation sur le partage du code source et motive les premières entités juridiques à le faire.

**Remarque :** L'expérience décrite dans **Instances connues** en est à ses débuts. Par conséquent, un **contexte résultant** ferme n'a pas encore été formé. Dans quelques mois, les effets de la licence InnerSource sur cet espace problématique seront plus clairs et cette section pourra être mise à jour.

## Instances connues

DB Systel a créé sa propre licence InnerSource, voir DB Inner Source License. Ils ont utilisé l'EUPL, car cela offrait une source ouverte comme point de départ, puis ont élaboré les contraintes et les règles supplémentaires requises dans leur contexte organisationnel spécifique.
Les premières entités juridiques (sociétés) au sein de la DB AG utilisent leur licence InnerSource.
Un effet positif qui se manifeste déjà est qu'il simplifie la conversation, surtout si certaines des parties impliquées ne connaissent pas l'InnerSourc
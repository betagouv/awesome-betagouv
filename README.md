# :sparkles: Awesome beta.gouv.fr

Une collection organisée d'outils et de ressources open source de la communauté beta.gouv.fr, conçus pour aider les équipes à construire des services publics numériques de qualité.

## Table des matières

- [Outils transverses](#outils-transverses)
- [Design System de l'État (DSFR)](#design-system-de-létat-dsfr)
- [Templates de projets](#templates-de-projets)
- [Outils pour le développement produit](#outils-pour-le-développement-produit)
- [Outils data](#outils-data)
- [Ressources communautaires](#ressources-communautaires)

---

## Outils transverses

Des outils et ressources essentiels utilisés dans tout l'écosystème beta.gouv.fr.

### Documentation

**Le guide complet de la communauté beta.gouv.fr**

Documentation exhaustive couvrant les bonnes pratiques, méthodologies et lignes directrices pour construire des services publics numériques.

🔗 [doc.incubateur.net](https://doc.incubateur.net)

### Sillon

**Livre blanc : "Propositions pour réaliser un produit numérique"**

Un cadre stratégique et des recommandations pour construire des produits numériques performants dans le secteur public.

🔗 [sillon.incubateur.net](https://sillon.incubateur.net)

### Standards

**Standards de qualité des produits numériques beta.gouv.fr**

Un ensemble complet de standards techniques et méthodologiques garantissant une qualité constante pour toutes les Startups d'État.

🔗 [standards.beta.gouv.fr](https://standards.beta.gouv.fr) | [Dépôt GitHub](https://github.com/betagouv/standards) 

### Dashlord

**Tableau de bord des bonnes pratiques techniques pour les Startups d'État**

Un outil de monitoring automatisé qui suit et affiche les indicateurs de santé technique, les métriques de sécurité et la conformité d'accessibilité des services numériques.

🔗 [Exemple de tableau de bord](https://dashlord.incubateur.net) | [Dépôt GitHub](https://github.com/socialgouv/dashlord)

### Espace-membre

**Le secrétariat numérique de la communauté**

Plateforme centralisée pour gérer les membres, les produits et les ressources de la communauté beta.gouv.fr.

🔗 [Accéder à l'outil](https://espace-membre.incubateur.net) | [Dépôt GitHub](https://github.com/betagouv/espace-membre-next)

### Peertube

**Les vidéos de la communauté**

Publiez des vidéos et consultez des précédents ateliers, formations...

🔗 [Accéder à l'outil](https://tube.numerique.gouv.fr/)

---

## Design System de l'État (DSFR)

Implémentations du Système de Design de l'État Français dans différents frameworks et langages.

### react-dsfr

**Composants React pour le DSFR**

Bibliothèque de composants React conformes au DSFR. Peut également être utilisée avec d'autres frameworks (Vue, Angular...) pour bénéficier du typage TypeScript du DSFR.

🔗 [Dépôt GitHub](https://github.com/codegouvfr/react-dsfr)

### vue-dsfr

**Composants Vue.js pour le DSFR**

Implémentation native du DSFR pour les applications Vue.js, offrant une intégration fluide avec l'écosystème Vue.

🔗 [Dépôt GitHub](https://github.com/dnum-mi/vue-dsfr)

### django-dsfr

**Intégration Django pour le DSFR**

Templates et composants Django conformes au DSFR pour construire rapidement des applications web gouvernementales avec Python.

🔗 [Dépôt GitHub](https://github.com/entrepreneur-interet-general/django-dsfr)

### dsfr-view-components (Rails)

**Composants Rails pour le DSFR**

Bibliothèque de View Components pour Ruby on Rails respectant les standards du Design System de l'État.

🔗 [Dépôt GitHub](https://github.com/betagouv/dsfr-view-components)

### Keycloak DSFR

**Thème DSFR pour Keycloak**

Thème d'authentification Keycloak aux couleurs et standards du DSFR pour une expérience utilisateur cohérente.

🔗 [Dépôt GitHub](https://github.com/codegouvfr/keycloak-theme-dsfr)

---

## Templates de projets

Des templates prêts à l'emploi pour démarrer rapidement vos projets.

De nombreux templates sont disponibles pour différentes technologies et cas d'usage, permettant de démarrer un projet conforme aux standards beta.gouv.fr en quelques minutes.

🔗 [Explorer les templates](https://github.com/betagouv/?q=template&type=all&language=&sort=)

---

## Outils pour le développement produit

Des outils techniques pour construire, sécuriser et déployer vos services numériques.

### sites-faciles

**Créez des sites conformes au DSFR sans coder**

Plateforme de création de sites internet conformes au Design System de l'État, sans compétences techniques requises et sans impact budgétaire important.

🔗 [Dépôt GitHub](https://github.com/numerique-gouv/sites-faciles)

### pdf-generator

**Service de génération de PDF**

Service de génération de documents PDF basé sur Puppeteer, idéal pour créer des rapports, factures ou attestations à partir de templates HTML.

🔗 [Dépôt GitHub](https://github.com/gip-inclusion/pdf-generator)

### antivirus

**Service de scan antivirus**

Service d'analyse antivirus basé sur ClamAV pour sécuriser les fichiers uploadés par vos utilisateurs.

🔗 [Dépôt GitHub](https://github.com/betagouv/signalconso-antivirus)

### publi.codes

**Langage déclaratif pour modéliser des domaines métiers**

Publicodes est un langage déclaratif pour modéliser des domaines métiers complexes en les décomposant en règles élémentaires simples. Parfait pour les simulateurs, calculateurs et moteurs de règles.

🔗 [Site officiel](https://publi.codes)

### geoip-api

**API de géolocalisation par IP**

Service qui retourne le code pays [ISO-3166-alpha2](https://fr.wikipedia.org/wiki/ISO_3166-1) d'une adresse IP, utile pour la localisation et l'analyse géographique.

🔗 [Dépôt GitHub](https://github.com/jdesboeufs/geoip-api)

### ds_proxy

**Proxy HTTP de chiffrement en streaming**

Proxy HTTP pour le chiffrement en streaming de fichiers stockés sur S3, garantissant la sécurité des données sensibles.

🔗 [Dépôt GitHub](https://github.com/demarches-simplifiees/ds_proxy)

### streaming-file-encryption

**Chiffrement/déchiffrement de fichiers en streaming**

Bibliothèque Node.js pour le chiffrement et déchiffrement de fichiers en streaming, simple et sécurisée.

🔗 [Dépôt GitHub](https://github.com/SocialGouv/streaming-file-encryption)

### oauth2-proxy + scalingo

**Intégration OAuth2 avec ProConnect**

Démonstration d'intégration de [oauth2-proxy](https://oauth2-proxy.github.io/oauth2-proxy/) avec ProConnect et Scalingo pour sécuriser vos applications.

🔗 [Dépôt GitHub](https://github.com/betagouv/oauth2-deploy-demo)

### Stack logging

**Solution de gestion des logs**

Stack complète de gestion des logs avec TimescaleDB + Vector + Metabase, déployable sur Scalingo pour un monitoring efficace.

🔗 [Dépôt GitHub](https://github.com/MTES-MCT/qualicharge-logs)

### odf.js

**Manipulation de documents ODF**

Boîte à outils pour lire et générer des fichiers ODF (.odt, .ods), permettant de travailler avec les formats de documents ouverts.

🔗 [Dépôt GitHub](https://github.com/odfjs/odfjs)

---

## Outils data

Des outils pour valider, standardiser et publier des données publiques.

### fr-format

**Validateurs pour formats français typiques**

Collection de validateurs pour vérifier la conformité des données aux formats français standards (SIRET, codes postaux, numéros de téléphone, etc.).

🔗 [Dépôt GitHub](https://github.com/datagouv/fr-format)

### schema.data.gouv.fr

**Schémas de données publiques et validation**

Collection de schémas pour les données publiques françaises avec outillage de validation, facilitant la standardisation et l'interopérabilité.

🔗 [Site officiel](https://schema.data.gouv.fr)

---

## Ressources communautaires

Des outils pour explorer et contribuer à l'écosystème beta.gouv.fr.

### BetaMap

**Cartographie de l'écosystème beta.gouv.fr**

Une cartographie interactive des produits numériques, des APIs et de la communauté beta.gouv.fr, alimentée par des données ouvertes.

🔗 [Démo interactive](https://betagouv.github.io/betamap) | [Code source](https://github.com/betagouv/betamap)

### Caldav2ICS

**Convertisseur CalDAV vers ICS**

Service de conversion sécurisé CalDAV → ICS sans stockage de données. Particulièrement utile pour convertir les calendriers de la Suite Numérique en format ICS exploitable.

🔗 [Service en ligne](https://caldav2ics.deno.dev) | [Code source](https://github.com/lsagetlethias/caldav2ics)

---

## Contribuer

Cette liste est ouverte à la contribution ! Pour ajouter un outil ou une ressource :

1. Forkez le dépôt
2. Ajoutez votre outil dans la catégorie appropriée
3. Assurez-vous qu'il soit open source et pertinent pour la communauté
4. Soumettez une Pull Request

---

## Licence

Cette liste est sous licence libre. Les projets référencés ont leurs propres licences, consultez chaque dépôt pour plus d'informations.

---

**Créé avec ✨ par la communauté beta.gouv.fr**

<img src="https://cdn.karnott.fr/logo-karnott-blanc.png" alt="Karnott" width="200"/>

# Développeur·se Backend Golang - Karnott
## Go, PostgreSQL et données géospatiales à grande échelle

**Lieu :** Lille (Euratechnologies) | **Contrat :** CDI | **Expérience :** 2 ans minimum | **Salaire :** 40-45K€ selon profil | **Télétravail :** 2 à 3 jours par semaine

---

## Karnott en quelques mots

Karnott développe un boîtier connecté qui se fixe sur n'importe quelle machine agricole pour enregistrer automatiquement les interventions terrain : hectares travaillés, kilomètres parcourus, temps de travail, trajets GPS, ou télémétrie machine. Fini les carnets papier.

Aujourd'hui, ce sont **des dizaines de milliers de matériels équipés** et **des milliards de points GPS collectés**. Notre plateforme web et notre app mobile permettent aux agriculteurs, ETA et CUMA, et aux viticulteurs de piloter leur activité en temps réel.

On traite de la donnée géospatiale à grande échelle, on la transforme en données utiles, et on construit les outils qui permettent à nos utilisateurs de prendre de meilleures décisions au quotidien.

---

## Le défi technique

Des dizaines de milliers de boîtiers qui remontent en continu. Des milliards de points GPS en base. Des calculs de surfaces et d'intersections sur des parcelles agricoles. Des séries temporelles qui grossissent tous les jours.

À cette échelle, une requête mal pensée ne ralentit pas : elle tombe. On travaille au quotidien sur l'indexation spatiale, le partitionnement des séries temporelles, les plans d'exécution et le tuning de la base. **Chez nous, la base de données n'est pas une couche de persistance qu'on oublie derrière un ORM : c'est là que se joue la performance du produit.**

Si ce type de problème t'intéresse plus que d'empiler des endpoints CRUD, on devrait bien s'entendre.

---

## Le poste

Tu rejoins l'équipe produit pour concevoir et faire évoluer les services backend qui alimentent notre plateforme. Concrètement :

- **Modéliser et optimiser notre base PostgreSQL** pour des volumes de données terrain qui grossissent en continu : schémas, index, requêtes, plans d'exécution
- **Concevoir et développer des APIs** performantes qui servent notre plateforme web, l'app mobile et nos intégrations partenaires
- **Traiter et valoriser de la donnée géospatiale** en temps réel et en batch
- **Opérer sur Google Cloud Platform** : déployer, monitorer, scaler les services
- **Participer aux choix produit** : chez Karnott, nous sommes au contact du terrain et des utilisateurs. Tu t'intéresses à la finalité du produit, tu as ton mot à dire sur ce qu'on construit et comment.

---

## Ce qu'on recherche

### Les deux incontournables

**Go (Golang)**

Ton langage principal. Tu sais écrire du code idiomatique, testable et maintenable.

**PostgreSQL, au-delà de l'ORM**

Tu es à l'aise avec la donnée elle-même, pas seulement avec la couche qui la masque. Concrètement, tu sais :

- lire un plan d'exécution (`EXPLAIN ANALYZE`) et comprendre pourquoi une requête est lente
- expliquer pourquoi un index existant n'est pas utilisé
- raisonner sur les transactions, les niveaux d'isolation et les verrous
- modéliser un schéma et assumer tes arbitrages : normalisation, contraintes, dénormalisation quand c'est justifié 
- tu as déjà optimisé une requête lente en production.

### Ce qui compte beaucoup

- **API REST / gRPC** : tu as conçu et maintenu des APIs en production, tu connais les enjeux de versioning, de performance et de documentation
- **Google Cloud Platform** : Cloud Run, Pub/Sub, BigQuery, Cloud Storage... tu es à l'aise dans un environnement cloud managé
- **Données géospatiales** : tu as manipulé du GPS, du GeoJSON, des projections ou des calculs de surfaces

### Ce qui s'apprend ici

Pas besoin de les maîtriser en arrivant, l'envie de monter en compétence suffit :

- **PostGIS** : les extensions spatiales de PostgreSQL, au cœur de nos calculs de parcelles
- **TimescaleDB** : nos séries temporelles, hypertables et politiques de rétention
- **Kotlin** : une partie de l'algorithme de valorisation de la donnée est en Kotlin. Tu n'as pas besoin d'être expert·e, mais tu es à l'aise pour lire et contribuer à du code dans ce langage
- **Claude** : tu sais tirer parti de l'IA pour accélérer ton développement, que ce soit pour générer du code, faire du refactoring ou documenter tes APIs

### Profil

- **Appétence produit forte** : tu ne codes pas juste des specs, tu comprends le problème utilisateur et tu proposes des solutions. Tu es curieux·se de savoir comment ce que tu construis est utilisé sur le terrain
- **Autonomie** : l'équipe est resserrée, chaque personne a un impact direct. Tu sais prendre des initiatives et porter un sujet de bout en bout. Nous sommes une équipe produit de moins de 10 personnes, avec une Product Manager, une UI designer, et des développeuses et développeurs avec des compétences Front, Mobile, Backend et Hardware.
- **Esprit d'équipe** : tu es à l'aise pour collaborer avec des profils variés, partager tes connaissances et apprendre des autres. La communication est fluide, directe et bienveillante. Nous effectuons des revues de code quotidiennes, nous partageons nos avancées en daily, et nous organisons des rétrospectives pour améliorer notre fonctionnement.
- **Pragmatisme** : tu privilégies les solutions simples et efficaces. Over-engineering n'est pas dans ton vocabulaire

---

## Stack technique

| Couche | Technologies |
| --- | --- |
| Backend | ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) |
| Base de données | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black) |
| Cloud | ![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) |
| Frontend | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white) |
| Mobile | ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black) |
| Infra | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white) |

---

## Processus de recrutement

1. **Échange téléphonique** (30 min)
2. **Entretien sur le fit humain et produit** (1h) : discussion avec l'équipe Care, et la Product Manager. On voit si nos valeurs et notre vision du produit sont alignées, et si tu te sens à l'aise dans notre équipe.
3. **Entretien technique** (1h) : discussion d'architecture, exercice de code, **et une partie modélisation de données et SQL**. On regardera ensemble un schéma, on parlera d'index, de plans d'exécution et de requêtes lentes.
---

**Intéressé·e ?** Envoie ton CV et quelques lignes sur ta motivation à **ludovic@karnott.fr** (CTO).
# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️
Une image Docker est un modèle en lecture seule, utiliser pour créer des conteneurs Docker. Elle est composée de plusieurs couches empaquetant toutes les installations, dépendances, bibliothèques, processus et codes d’application nécessaires pour un environnement de conteneur pleinement opérationnel.
On crée le fichier Dockerfile contenant les instructions nécessaires afin de construire (build) une image docker. Une image docker est construite en exécutant la commande "docker build --tag example-app .". Cette dernière exécutera les lignes de commande se trouvant dans le fichier dockerfile.

- l'éxécution d'un container ✔️
Pour démarrer un conteneur de façon détachée, on utilise la commande "docker run -d example-app".

- l'orchestration de containers avec docker-compose ✔️
Docker compose c'est un outil qui permet d'exécuter de manière simple plusieurs conteneurs intercommunicants. Il utilise le fichier docker-compose.yml pour définir divers services. Le format est YAML.

Exemple d'un fichier docker-compose.dev.yml :
```
services:
    server:
        build: ./server
        ports: 
            - 5050:5000
        command: npm run dev
        volumes: 
            - ./server/src/:/app/src/
    mongodb:
        image: mongo
        volumes: 
            - ./data:/data/db
 ```

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Docker

- [install Docker desktop](https://www.docker.com/get-started/)

### Docker compose

- [Docker compose doc](https://docs.docker.com/compose/compose-file/ )

### DockerHub

- [Docker Hub: library and community for container image](https://hub.docker.com/)


## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

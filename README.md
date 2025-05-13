# Next.js Docker Templates
Un ensemble de templates Docker optimisés pour les applications Next.js, avec une approche multi-stage build pour des déploiements plus efficaces et sécurisés.

## À propos <a href="https://nextjs.org/"> <img src="https://raw.githubusercontent.com/dnh4/next_docker_template/refs/heads/main/images/next.png" height="30" alt="Logo Next"></a> <a href="https://www.docker.com/"> <img src="https://raw.githubusercontent.com/dnh4/next_docker_template/refs/heads/main/images/docker.png" height="30" alt="Logo Docker"></a>

Ce repository contient des templates Docker soigneusement conçus pour les applications Next.js. L'objectif est de fournir des configurations Docker prêtes à l'emploi qui suivent les meilleures pratiques, optimisent la taille des images et améliorent la sécurité.

## Fonctionnalités

- **Multi-stage builds** : Séparation des étapes de construction et d'exécution pour des images plus légères
- **Configurations optimisées** : Paramètres ajustés pour les meilleures performances
- **Sécurité renforcée** : Utilisation d'utilisateurs non-root, réduction de la surface d'attaque
- **Variants adaptés** : Templates pour différentes configurations de Next.js (statique, SSR, etc.)
- **Cache optimisé** : Stratégies efficaces de mise en cache pour des builds plus rapides

## Comment utiliser ces templates
- Clonez ce repository ou téléchargez le template qui vous intéresse
- Copiez le Dockerfile dans votre projet Next.js
- Ajustez les variables d'environnement ou les paramètres si nécessaire
- Construisez votre image Docker

```
# Exemple pour construire une image avec le template standard
docker build -t my-nextjs-app .
```
## Licence
**MIT**
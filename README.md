# Mini projet de site statique avec K8S

Dans ce projet un object deployment ainsi que service est crée afin de déployer un cluster K8S exposant un site statique.

## Objet deployment

L'objet deployment à pour rôle de déployer le cluster ainsi qu'un replica afin de maintenir en permanence 3 pod.

## Objet service

L'object service déploie quand à lui le service NodePort afin de rendre notre cluster accessible vers l'extérieur

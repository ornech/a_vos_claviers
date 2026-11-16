# Podman

## Installation de Podman

`apt install podman`

## vérifier information d’installation

`podman info`

## Lancer un conteneur

`podman run -d --name <nom_à_attribuer> -p <port>:<port> <image_linux>`

## Démarrer, arrêter ou redémarrer un conteneurs

```podman start <id_conteneur>
   podman stop <id_conteneur>
   podman restart <id_conteneur>
```

## Suprimmer un conteneur

`podman rm <nom_conteneur>`

## Lister les conteneurs

`podman ps`
`podman ps -a`

## Télécharger une image

`podman pull <image>:<version>`

## Suprimmer une image

`podman rmi <image>:<version>`

## lister les images locales

`podman images`


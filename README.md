# changeColor

Cette page change aléatoirement la couleur de fond du la page !

Pour l'allumer :

création de l'image : 

    - docker build -t nomdevotreimage .    (le "." symbolise le fait que vous êtes dans le dossier du projet en question lorsque vous exécutez la commande)

création du container : 

    - docker run -p 3000:80 --name nomDuContainer nomdevotreimage

    Avec :
    nomdevotreimage représentant l'image créée avec la commande précedente
    Il s'agit du port 80 car l'image est basée sur Nginx

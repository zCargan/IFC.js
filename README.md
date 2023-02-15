IFS.js est une librairie javascript permettant de lire des fichiers ifc dans un navigateur web

Après quelque recherche, j'ai trouver comment utiliser cette librairie pour un projet.

Installer les dépendances à l'aide de la commande :

```ǹpm install```

Tout d'abord, si vous suivez le documentation ci jointe, une ligne doit être ajouter au fichier pakcage.json :

Veuillez ajouter ceci à la fin du document :

``` "type": "module" ```

Ensuite, veuillez vous rendre à cette adresse suivante :

``` /node_modules/three/examples/jsm/controls ``` 

excecuter la commande suivante :

``` cp OrbitControls.js OrbitControls ``` 

Maintenant, rendez vous à l'adresse suivante :

``` /node_modules/three/examples/jsm/utils/ ``` 

excecuter la commande suivante :

``` cp BufferGeometryUtils.js BufferGeometryUtils ``` 

Une fois toute ces étapes faites, vous pouvez maintenant utiliser la commande :

``` npm run build ``` 

Un fichier bundle.js devrait être apparu.

Accéder à votre fichier ``` index.html ``` et clique sur ``` /src ``` afin de commencer à pouvoir explorer la librairie [IFC.js](https://ifcjs.github.io/info/) 

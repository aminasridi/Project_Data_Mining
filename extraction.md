1. Extraction des données Twitter
Afin d'extraire des tweets pour une analyse,on va accéder à un compte « Twitter Developer » et créer une application.
On va Télécharger les Tweets en utilisant l’API de twitter.Pour cela,on va télécharger au moins 10 mille tweets.
À partir de cette application on va utliliser les informations suivantes:

-Consumer Key (API Key)
-Consumer Secret (API Secret)
-Token
-Access Token Secret
On va créer une fonction pour nous permettre l'authentification de nos clés.(Configuration de l'API: Authentification et accès et Retourne l'API avec authentification)
Après cela, on va extraire la quantité des tweets et puis on a des informations pour construire un pandas DataFrame, afin de manipuler les informations de manière très simple.
On affiche les 10 premiers éléments du dataframe:

![Capture](https://user-images.githubusercontent.com/24653616/102355697-81d3d380-3fac-11eb-8e15-b790620e3f1e.PNG)

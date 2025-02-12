# <p align="center">  🦖🦖🦖 ♡ ```Projet Python``` <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/4e803fb5-d22d-4b01-8f5e-054041544a26/d2yw9ll-6b1e490c-c880-44bb-ba3b-7c77d34899b7.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzRlODAzZmI1LWQyMmQtNGIwMS04ZjVlLTA1NDA0MTU0NGEyNlwvZDJ5dzlsbC02YjFlNDkwYy1jODgwLTQ0YmItYmEzYi03Yzc3ZDM0ODk5YjcucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.UYJQmnU7Vy-zPUhySWX1TDCBjNJl-sPxVqfUw-j7Uq0" alt="alt text" width="90" height="whatever">  </p> 
## Comment faire ?

1. **DOCKER**

- Cloner mon projet : ```git clone https://github.com/ay-belbachir/dockerVolUtility.git```, puis ```cd dockerVolUtility```
- À la racine du projet, exécuter : ```docker compose up -d```, puis rendez-vous sur [http://localhost:8080](http://localhost:8080)
- Ajouter vos dumps et plugins dans le répertoire du projet cloné, qui est en réalité un répertoire partagé entre votre conteneur et votre machine : ```plug-dump/```
- Cliquer sur ```ADD PLUGINS``` pour les plugins de Volatility le path est **/plug-dump/plugins**. Pour Volatility 2, le path est **/volu/plug-dump/overlays**.
- Une fois le dump ajouté au volume, cliquer sur **New** pour l'ajouter au scan.

  <img src="https://github.com/ay-belbachir/dockerVolUtility-/blob/main/asset/capt.png" width="200" > 

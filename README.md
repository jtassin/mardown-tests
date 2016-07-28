# wpartp

worldpress artprice

avant de lancer l'appli il faut recupérer la db et la placer dans ./mysql

start  : docker-compose up -d

stop :  docker-compose down 


## Procédure pour récreer la DB wordpress

* Telecharger le script rename sur : https://interconnectit.com/products/search-and-replace-for-wordpress-databases/
* Le déplacement dans le rep wordpress
```sh
scp -r /tmp/wp/rename/ root@prweb1:/var/www/wpartp/wp/
```
* Aller sur http://<host>/rename
* Remplacer wpdev.artprice.bil vers <host>
 
 

# Ynov - M2 Elective Docker

### Attendu

Creation d'une infra avec la techno que vous voulez:

- Choisir parmis : python / java / js / php / ruby / go / erlang
- Un frontend avec une page HTML : Hello-World + Compteur de visite. ( / ) 
- Un Backend avec une bdd ( mongo / mysql / postgre )
	=> une API qui enregistre en bdd un client lorsque l'on lance url /put_name/$un_nom e
	==> Ce $un_nom devra être enregistré en BDD dans une table/collection nommée name.
- Un container redis pour stocker un compteur de visite 

==> 15/20

- personnalisation de l'infra avec Kibana ou tout autre système de monitoring / recup de logs  

==> 5/20

A RENDRE AVANT LE 2 NOV 2020 00H00.

### Rendu

Cloner le dépot, puis
```bash
docker-compose up
```

Liens du projet :

| Service | URL |
|---|---|
| application | http://localhost  |
| monitoring | http://localhost:9090 |

- Q.3.1: le materiel A est un switch. il permet le passage des données entre les ordinateurs. 
- Q.3.2: le materiel B est un routeur. il permet ici au reseaux ```10.10.0.0``` de communiquer vers d'autre reseaux sois le ```10.12.0.0``` ou plus loin vers le ```172.16.5.0```.
- Q.3.3:  f0/0 et g1/0 sont les 2 interfaces de B respectivement f0/0 permet de voir le reseau ```10.10.0.0``` et ```10.11.0.0``` et g1/0 permet de voir le reseau ```10.12.2.0```.
- Q.3.4: /16 du pc2 represent son cidr. montrant le nombre d'adresse disponible pour cette plage
- Q.3.5: ```10.10.255.254``` represente la passerelle du pc2 vers le reseaux exterieur
- Q.3.6:
  |Ordinateur|L'adresse de réseau|La première adresse disponible|La dernière adresse disponible|L'adresse de diffusion|
  |----------|-------------------|------------------------------|------------------------------|----------------------|
  |PC1|10.10.0.0|10.10.0.1|10.10.255.254|10.10.255.255|
  |PC2|10.11.0.0|10.11.0.1|10.11.255.254|10.11.255.255|
  |PC5|10.10.0.0|10.10.0.1|10.11.255.254|10.11.255.255|

- Q.3.7: les pc 1 3 4 5 son sur le meme reseaux donc vont pouvoir communiquer. le pc2 quand a lui est sur un autre reseaux donc se verra lui meme.
- Q.3.8: ayant tous la meme adresse ip en passerelle ils peuvent tous acceder au reseaux ```172.16.5.0/24```
- Q.3.9: Il n y a aucune incidence.
- Q.3.10: il faudrais rajouter un dhcp ou verifier si le routeur a un dhcp integre, configurer une plage d'adresse et mettre les ordinateur en adressage ip automatique. ainsi toute machine que se connectera au reseau se verra attribuer automatiquement une adresse ip.
- Q.3.11: ```00:50:79:66:68:00``` ---> PC1
- Q.3.12: oui la communication a reussi car on a une reponse au paquet no6 reponse de 00:50:79:66:68:03 sois le PC4.
- Q.3.13: la request vien du PC1 ```00:50:79:66:68:00``` et le reply du ```00:50:79:66:68:03``` PC4
- Q.3.14: Le protocol ARP. transporter le protocol ip vers la bonne machine
- Q.3.15: le materiel A permet le transport des donnees et le B aucun on est sur le meme reseaux
- Q.3.16: le PC3 ```10.10.80.3/16``` initialise la communication.
- Q.3.17: ICMP envoyer un message d'erreur quand la communication na pas aboutie.
- Q.3.18: Non car les 2 machine ne sont pas sur le meme reseaux.
- Q.3.19: la machine portant l'addresse 10.10.255.254 sois la dernier du reseau 10.10.0.0/16   a essaye de joindre le pc3 du meme reseaux. communication n'ayant pas abouti car la machine n'existe pas( dans le reseaux presenter) ou est eteinte.
- Q.3.20: les materiels A et B nont servis a rien car la machine ayant l'addresse 10.10.255.254 n'est pas presente dans notre reseaux.
- Q.3.21: Source ```10.10.4.2``` PC4 et destination ```172.16.5.253``` serveur
- Q.3.22: Source ```ca:01:da:d2:00:1c``` et destination ```CA:03:9E:EF:00:38``` j'en deduis que le PC4 est passer par le routeur B ensuite le R2 pour atteindre le serveur
- Q.3.23: entre B et R2

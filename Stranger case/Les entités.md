# Rapport d'enquête Mission ESUBIO challenge CTF OSINT Starnger Case

## 1. Les Entités prenant part a l'affaire.

![logo_esubio](https://user-images.githubusercontent.com/95431446/168475454-3e27c785-0e4d-43df-b0ad-bf30924399f6.png)

🌐 - https://esubio.fr/
🐦 - https://twitter.com/Esubio_off/
🔗 - https://www.linkedin.com/company/esubio/

### ESUBIO (École Supérieure de Biotechnologie) est une école bretonne spécialisée en biotechnologie. Institut supérieur, il emploierait entre 2 et 10 employés.

Active depuis plus de 2 ans et comptant plus de 6 partenaires, l’école a, pour l’instant, recrutée plus de 25 élèves.

L'organigramme connu de l'université est le suivant : 
![ESUBIO](https://user-images.githubusercontent.com/95431446/168498399-d426c7d2-3ee3-4793-930f-207c7e253713.png)

- LECARPENTIER Charles.

L’université est dirigée depuis ses débuts par LECARPENTIER Charles. Ancien chercheur, il s’est depuis reconverti. Monsieur LECARPENTIER a une certaine vision de la France, très positionnée à droite et  n’hésite pas à en faire part sur tous ses réseaux, voire même à montrer certaines affinités pour certains partis, notamment celui de la France Libre, sur lequel nous reviendrons plus tard.

| ![image](https://user-images.githubusercontent.com/95431446/168496971-5cc9bcef-ddd2-4cf3-821a-791938f551d2.png) | 
| :------------------------- |
| LECARPENTIER Charles | 
🔗 [Linkedin](https://www.linkedin.com/in/charles-lecarpentier-880b7b239/)
🐦 [Twitter](https://twitter.com/Charles_Lecarp)

 - POTVIN Thierry.

Pour diriger l’école, Charles peut compter sur Thierry POTVIN, responsable relation et développement chez ESUBIO. Fan de musique (notamment collectionneur de vinyle) et de voyage, Thierry n’hésite pas à afficher ses passions sur ses réseaux et ne se retient pas non plus d’afficher ses convictions politiques. Il semble, tout comme Charles, être orienté vers une droite forte, l’extrême droite. Voulant partager sa passion au monde entier, monsieur POTVIN est à l’origine d’un blog (https://mypassionforvinyles.fr/), qui est encore en cours de développement. qui est encore en cours de développement. Ce blog contient un lien en .onion caché, qui semble être utilisé à de mauvaises fins.

| ![image](https://user-images.githubusercontent.com/95431446/168497267-c7efe98d-e28a-4d18-b898-f93450deac0a.png) |
| :---------------------------: |
| POTVIN Thierry |
🔗 [Linkedin](https://www.linkedin.com/in/thierry-potvin-8a5b81239/)
🐦 [Twitter]([https://twitter.com/ThyPotvin)
🎶 [Site perso](https://mypassionforvinyles.fr/)

- Les étudiants

La plupart des étudiants n’est pas trouvable sur les réseaux sociaux. Néanmoins, certains d’entre eux  ont pu nous donner des éléments décisifs. C’est notamment le cas de Julien Rouve. Très actif sur les  réseaux sociaux, nous avons pu, et ce, grâce à son instagram, remonter jusqu’à un serveur discord dans lequel il se trouvait avec Julien Borleau.

Julien Borleau a lui aussi été très utile pour cette investigation. À partir de son pseudo Discord, nous avons pu remonter jusqu’à un TRELLO de projet. En groupe avec Julien Rouve et un certain Martin, Julien Borleau travaillait sur le RFC. Ayant eu besoin d’un RETEX d’un professionnel, ils ont fait appel à Wen Mai Baizuo, chercheuse en biologie chez Laboratoire Lemery. Nous reviendrons plus tard sur ce laboratoire.

Alexandre Trevisani nous aura également beaucoup aidé. Inquiet pour ses camarades, il sera le premier à avoir signalé de mystérieuses disparitions sur son twitter et réitèrera cette démarche lors d’une story Instagram.

______________________________________________________________________________________________________________________________________________

![image](https://user-images.githubusercontent.com/95431446/168497718-0625c75f-3adb-4efe-ab44-b7ee62ddbc5b.png)

🐦 : https://twitter.com/partilafrlibre 
🌐 : https://partilafrancelibre.fr/

### La France Libre est un parti politique militant pour “la fin de l'enchaînement démocratique”.

Le parti politique « La France Libre » est un parti d’extrême-droite française. Bien décidé à « libérer le peuple », ce parti semble bien décidé à aller au bout de ses idées.

On remarque principalement deux personnes au sein de ce parti :

- Le premier, monsieur CHAUVET Romain. C’est notamment lui qui est très proche de monsieur LECARPENTIER, directeur de l’école. Il n’y a rien de particulier à noter, si ce n’est ses idées virulentes.

| ![image](https://user-images.githubusercontent.com/95431446/168578578-70a1fe94-855a-418a-bd52-7ed5e58d935b.png) |
| :---------------------------: |
| CHAUVET Romain |
🔗 [GitHub](https://github.com/powermindctrl)
🐦 [Twitter](https://twitter.com/romainchauvet15)
✉️ [Mail](romain.chauvet@partilafrancelibre.fr)

- Le second, monsieur GOULET Olivier. Bien plus discret, il ne possède aucun réseau social et n’est trouvable que sur le site de la France Libre. Il possède également un github et a contribué à un projet du laboratoire Lemery à travers un fichier de participation financière ; sous-entendant alors que LaFranceLibre paierait le laboratoir.

🔗 [GitHub](https://github.com/Anstarke67/Lemery/commit/75245486359c95643453edf8fb9383f479b738a5)

Dès lors, il semble clair que la France Libre est très proche de l’école ainsi que de Lemery.

______________________________________________________________________________________________________________________________________________

![image](https://user-images.githubusercontent.com/95431446/168577139-18cc74e7-849e-4670-bc26-cd48af48556c.png)

🌐 : https://laboratoirelemery.fr/
📞 : 07 80 91 24 67

### Le laboratoire Lemery est un laboratoire spécialisé en recherche et en innovation.

Nous avons notamment pu trouver des informations sur Benoit Dormont, directeur de recherche. Cette personne semble très active sur Linkedin et possède également un GITHUB sur lequel elle partage des cours de neuroscience. Mais également des contenus bien plus sombres. En effet, son github affiche des expérimentations du cerveau, faites sur des cobayes et financées par « LFL ». L’adresse IP trouvée sur un code mène quant à elle à l’école. À partir de son pseudo (trouvable sur son github), on peut trouver qu’il cherche de l’aide pour de l’électronique, concernant la puce que son laboratoire est en train de mettre en place.

Son Github contient également des logins pour accéder au .onion caché dans le blog de Thierry.

| ![image](https://user-images.githubusercontent.com/95431446/168611811-7525010e-c749-4d5a-9bd2-5a4de857409b.png) |
| :---------------------------: |
| CHAUVET Romain |
🔗 [GitHub](https://github.com/powermindctrl)
🔗 [Linkedin](https://www.linkedin.com/in/benoit-dormont-304985239/)

Puis vint madame AIZUO Wen Mai, que nous avons abordée précédemment. Chercheuse en biologie, elle semble liée à l’affaire mais nous n’en avons aucune preuve directe (si ce n’est qu’elle a aidé des élèves sur un projet).

| ![image](https://user-images.githubusercontent.com/95431446/168612362-e40e0cd1-30da-447d-bb70-e47cfee20db1.png) |
| :---------------------------: |
| AIZUO Wen Mai |

La dernière personne est monsieur BRUZOIS Mathieu, Directeur de publication, il semble être très proche de monsieur DORMONT, comme le prouve leur séminaire ensemble à Rennes.

______________________________________________________________________________________________________________________________________________

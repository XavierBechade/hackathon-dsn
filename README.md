# Hackathon DSN 
# Equipe DGEFP - DNUM 

Dépôt pour le Hackathon DSN organisé par la Direction interministérielle du numérique.

**📙 Retrouvez le Guide du participant sur Outline en cliquant [ici](https://documentation.beta.numerique.gouv.fr/doc/guide-hackathon-dsn-Vvxa7bq3O0)**


Ce dépôt est utilisé pour l'évaluation du  projet DGEFP-DNUM à l'issu du Hackathon ! 


## 🌸 Rendu

Pour évaluer le  proje le README est complété avec les informations suivantes : 

### Description

En France, le nombre d’apprentis continue de progresser autant dans le secteur public que privé. L’apprentissage est un tremplin pour s’insérer dans le monde du travail, il donne accès à de nombreux métiers dans des secteurs très variés.

Les enjeux de politique publique sont forts, avec un besoin d’information pour l’orientation et le choix des filières Les choix de secteurs et d’entreprises sont complexes et de nombreux contrats d’apprentissage ne sont pas menés à terme.. 

Sur l’échantillon traité pendant le hackathon 
- 33% des contrats d’apprentissage sont rompus avant la fin prévisionnelle
-  20% des apprentis ayant finalisé leur apprentissage n’ont pas obtenu de contrat de travail à ce jour


### Solution

L’objectif du projet « trajectoire apprentissage » est d’enrichir l’information du dispositif en fournissant des indicateurs sur le devenir des apprentis à l’issue de leur contrat d’apprentissage (contrat de droit commun, dans l’entreprise ou dans le secteur d’activité, etc..). 

Il produit des indicateurs rapprochant  les contrats d’apprentissage et les contrats conclus à la sortie du dispositif, pour : :  
- Proposer un tableau de bord de pilotage du dispositif d’apprentissage enrichi avec les données de la DSN
- Permettre d’identifier le taux de réussite d’un nouveau contrat d’apprentissage (algorithme apprentissage supervisé)

L’usage des données est le suivant, à partir des données de la DSN :
- Identifier les indicateurs liés aux contrats d’apprentissage rompus et aux contrats de travail des apprentis à la suite de leur apprentissage
- Sélectionner les différentes caractéristiques de l’apprenti et de l’entreprise nécessaire à l’apprentissage du modèle de prédiction.


### Impact envisagé

Une amélioration de la connaissance des parcours est attendue grâce à une information plus précise des apprentis et futurs apprentis sur les perspectives d’emploi et les débouchés après leur formation. Elle doit permettre une meilleure qualité de l’orientation et du projet professionnel, mesurable par le taux d’aboutissement des contrats d’apprentissage. 

La solution permettra de mettre à disposition : 
- Un tableau de bord pour visualiser les indicateurs
- Un algorithme pour prédire le taux de réussite d’un contrat d’apprentissage

Les usagers visés sont : 
OPCO et CFA lors de la validation d’un contrat d’apprentissage et pour un suivi sur leur périmètre
Apprentis et futurs apprentis afin de percevoir les perspectives de leur formation
DGEFP pour le pilotage national


### Ressources


### Retours sur la qualité des données exploitées

La date de fin de contrat a été initialement envisagée comme critère de filtre mais elle ne s’est pas avérée fiable pour identifier un contrat rompu. En effet, certaines entreprises ne renseignent pas la date de fin de contrat réelle n’est pas toujours renseignée et la date de fin prévisionnelle n’est pas qualitative.. 

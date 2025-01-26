# iut_sd2_powerbi_enedis

Ce repository contient un ensemble de fichiers en lien avec un projet de création d'un tableau de bord sur le logiciel **PowerBI**, dans le cadre de la deuxième année du BUT SD.


## 📄 Présentation du projet

Ce projet a pour objectif de créer un tableau de bord interactif et visuel sur **Power BI** afin d'analyser de manière générale les performances énergétiques des habitations et des bâtiments situés dans le département du Rhône. 


## 📂 Fichiers 
Vous pouvez retrouver dans ce repository :

* **Documentation Technique.docx** : Un fichier Word décrivant les fonctionnalités techniques du tableau de bord 

* **Documentation Fonctionnelle** : Un fichier Word expliquant les principales fonctionnalités pratiques du dashboard 

* **DonneesRhoneEnedisCorV2.csv** : Un fichier csv contenant toutes les données nécessaires pour le fonctionnement et les analyses statistiques de l'application

* **Tableau de Bord Enedis GreenTech.zip** : Un fichier zip qui contient notre tableau de bord sous PowerBI 


## 🛠️ Fonctionnalités clés

- ✅ **Menu et navigation avancée** : 
	* Mise en place d'un design simple et clair, accordé au thème du projet 
	* Onglets et navigation entre les pages du tableau de bord dynamique et interactive par rapport aux actions de l'utilisateur 
	* Filtres hiérarchiques et dynamiques permettant d'analyser les données énergétiques d'une ou plusieurs localisations précises de la commune du Rhône


 - ✅ **Visualisation dynamique** : 
	* Cartographies afin de visualiser géographiquement la répartition des étiquettes DPE et GES de l'ensemble des bâtiments
	* Graphiques interactifs pour explorer les données de performances énergétiques (Consommation, Émissions, Coûts)
	* Filtres hiérarchiques et dynamiques permettant d'analyser les données énergétiques d'une ou plusieurs localisations précises de la commune du Rhône
	* Mise en place d'une page permettant de comparer, selon des scripts DAX, la performance énergétique entre deux villes choisies par l'utilisateur 


- ✅ **Modélisation des données** : 

	* Extraction des données par requêtes API
	* Nettoyage de la base de données initiale des logements et agrégation de leurs caractéristiques via PowerQuery
	* Création d'une modélisation des données en étoile afin d'assurer une optimisation de la gestion de ces dernières par le logiciel


## 📥 Données utilisées


- **API publique du jeu de données : DPE Logements existants (depuis juillet 2021)** : Données publiques fournies par le gouvernement français ou les collectivités locales sur les étiquettes DPE et GES des logements existants en France. (https://data.ademe.fr/datasets/dpe-v2-logements-existants/api-doc)

- **API publique du jeu de données : DPE Logements neufs (depuis juillet 2021)** : Données publiques fournies par le gouvernement français ou les collectivités locales sur les étiquettes DPE et GES des logements neufs en France. (https://data.ademe.fr/datasets/dpe-v2-logements-neufs/api-doc)



## ⚙️ Installation / Utilisation


Il y a deux manières à ouvrir le tableau de bord :

### ⬇️ Télécharger l'application et l'ouvrir localement 

Si vous voulez l'utiliser **localement**, vous devez donc télécharger les fichiers suivants du repository :

* **DonneesRhoneEnedisCorV2.csv** : Le fichier csv contenant toutes les données du tableau de bord

* **Tableau de Bord Enedis GreenTech (Mekki C Oussama N Ilan F).zip** : Un fichier zip contenant le dashboard, à ouvrir dans PowerBI

*N'oubliez pas d'abord de paramétrer l'emplacement de la source des données lors de la première ouverture du tableau de bord*

### 🔗 Accès à l'application en ligne 

Vous pouvez également directement visualiser l'application **en ligne** via PowerBI App grâce au lien suivant :



*L'accès en ligne est seulement disponible pour ceux ayant les autorisations requises*


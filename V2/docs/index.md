# Guide Data Inra <!-- version à automatiser -->

Ce guide permet de faire un tour rapide des fonctionnalités du portail de données de l’INRA Data Inra, basé sur la version 4.9.2 de Dataverse. Il est régulièrement mis à jour.

Pour toute question contacter datainra@inra.fr 

## Organisation des données dans Data Inra
Un **jeu de données** (ou “**dataset**”) est un objet identifié par un DOI (et donc citable comme un objet unique), décrit par des métadonnées, et associé, ou non, à un ou plusieurs fichiers de données (il peut s’agir des données elles-mêmes, de documentation, de code…). Si les données sont déposées dans un autre entrepôt, le lien vers celles-ci sera précisé dans une métadonnée dédiée : Link to data. 
Un **fichier** (ou “**File**”) est toujours associé à un dataset. 

Un **dataverse** est un conteneur pouvant regrouper des datasets et/ou d’autres dataverses. Il peut être créé pour un projet, un collectif, un domaine scientifique... 
La page d’accueil du portail Data Inra est située au niveau du dataverse racine sous lequel sont placés les autres dataverses selon une organisation arborescente.

## S’authentifier avec son Ldap Inra et gérer son compte
\[...\]

### Exemple de Note de Bas de Page : nécessite une extension
Cette page permet :
- d’afficher et d’exporter la citation du fichier. Celle-ci est basée sur la citation du dataset (le DOI et la version sont ceux du dataset), à laquelle s’ajoutent le nom du fichier et son empreinte numérique (selon le format du fichier UNF[^1] : universal numeric fingerprint ou MD5).

[^1]: L’UNF: universal numeric fingerprint, est une petite chaîne de caractères alphanumériques de
longueur fixe résumant le contenu de l’ensemble de données. Toute modification des données, aussi minime soit-elle, entraîne une nouvelle signature électronique universelle. L’UNF assure la non corruption du fichier.

### Exemple de tableau (non stylisé)
<table>
	<tr> <!--Titres-->	
		<th></th>
		<th>AddDataverse</th>
		<th>AddDataset</th>
		<th>ViewUnpublishedDataverse</th>
		<th>ViexUnpublishedDataset</th>
		<th>DownloadFile</th>
		<th>EditDataverse</th>
		<th>EditDataset</th>
		<th>ManageDataversePermissions</th>
		<th>ManageDatasetPermissions</th>
		<th>PublishDataverse</th>
		<th>PublishDataset</th>
		<th>DeleteDataverse</th>
		<th>DeleteDatasetDraft</th>
	</tr>
	<tr> <!--Admin-->
    	<th>Admin</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    </tr>
	<tr> <!--Contributor-->
    	<th>Contributor</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th>+</th>
    	<th>+</th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th>+</th>
    </tr>
	<tr> <!--Curator-->
    	<th>Curator</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th>+</th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th>+</th>
    </tr>
	<tr> <!--Dataset Creator-->
    	<th>Dataset Creator</th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    </tr>
	<tr> <!--Dataverse + Dataset Creator-->
    	<th>Dataverse + Dataset Creator</th>
    	<th>+</th>
    	<th>+</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    </tr>
	<tr> <!--Dataverse Creator--> 
    	<th>Dataverse Creator</th>
    	<th>+</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    </tr>
	<tr> <!--File Downloader-->
    	<th>File Downloader</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th>+</th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
    	<th></th>
	</tr>
	<tr> <!--Member-->
    		<th>Member</th>
    		<th></th>
    		<th></th>
    		<th>+</th>
    		<th>+</th>
    		<th>+</th>
    		<th></th>
    		<th></th>
    		<th></th>
    		<th></th>
    		<th></th>
    		<th></th>
    		<th></th>
    		<th></th>
    </tr>
</table>

### Exemple d'Image
![Exemple](img/logIn_homepage.png)

# Projet-ssis-ssas-power-bi
Ce projet est un cube SSAS (SQL Server Analysis Services) qui analyse les données du modèle AdventureWorks. Il inclut des requêtes MDX pour interroger le cube et obtenir des informations sur les ventes, les produits et les clients. 

Le projet est structuré comme suit :
- **Cube SSAS** : Le cube contient des dimensions et des mesures de données liées aux ventes, aux produits et aux clients.
- **Requêtes MDX** : Des requêtes MDX sont utilisées pour extraire des données spécifiques du cube.
- **Solution** : Le fichier `.sln` contient tous les projets nécessaires pour ouvrir et travailler avec le cube SSAS et les requêtes MDX dans **Visual Studio** ou **SQL Server Data Tools**.

## Prérequis
Pour exécuter ce projet, vous devez avoir installé :
- **Visual Studio** avec les outils de développement SQL Server ou **SQL Server Data Tools**.
- **SQL Server Analysis Services (SSAS)** installé et accessible.
- **AdventureWorks Database** installé sur votre serveur SQL Server.

## Instructions pour déployer
1. Ouvrez le fichier **.sln** dans Visual Studio.
2. Si vous utilisez un cube SSAS, assurez-vous que la connexion à votre serveur SSAS est correctement configurée.
3. Déployez le cube en cliquant droit sur le projet SSAS dans l'Explorateur de solutions et en sélectionnant **Déployer**.
4. Exécutez les requêtes MDX dans Visual Studio ou SQL Server Management Studio (SSMS).

## Déploiement du Cube
Pour déployer le cube SSAS sur un serveur :
1. Allez dans l'Explorateur de solutions.
2. Faites un clic droit sur le projet SSAS et sélectionnez **Déployer**.
3. Si le cube est bien configuré, il sera déployé et accessible via SSMS ou Power BI.

## Utilisation des requêtes MDX
Les requêtes MDX peuvent être exécutées dans **SQL Server Management Studio (SSMS)** ou directement dans Visual Studio pour analyser les données du cube.

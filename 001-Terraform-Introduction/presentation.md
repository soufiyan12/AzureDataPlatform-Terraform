# Terrafom , c'est quoi ?? ( By Hashicop)
+ Management d'infrastructure
+ Construire, Modifier ou supprimer une ressource x
+ Versioning

# Plusieurs providers de differents type <( https://registry.terraform.io/browse/providers)>
+ AWS, Azure, GCP, Confluent Cloud

# Language utilise HCL ( Hachicorp Config Language)

# Programmation Declaratif ( vise la cible Etat final )

# Utilisation 
+ IAC Infrastructure As Code
+ Automatisation
+ CI/CD

# Structure des fichiers 
+ provider.tf
+ main.tf
+ variables.tf

# Gestion des variables
+ cmd -var variable="value"
+ cmd -var-file="file.tfvars"
+ 
+ TF_VAR :
+ terraform.tfvars
+ terraform.tfvars.json
+ *.auto.tfvars
+ *.auto.tfvars.json
+ 

# terraform.tfstate : 
+ Contient une correspondance entre les ressources dans fichier de configuration et leur représentation réel 
+ Permet de comparer entre l'etat existant et les changements ajoutee au fichier de conf*

# Les etapes cles de terraform
+ init 
+ validate
+ plan
+ apply








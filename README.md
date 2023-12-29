# Gestion de Banque

Ce programme de gestion de banque a été développé en langage C pour gérer les comptes bancaires. Il offre des fonctionnalités de base telles que la création de nouveaux comptes, la modification, la consultation, et la suppression de comptes, ainsi que des fonctionnalités supplémentaires telles que l'affichage de la liste de tous les comptes, la somme totale des soldes et le nombre total de comptes.

## Fonctionnalités
**Mot de passe :** il faut tout d'abbord entrer le mot de passe pour acceder a la plateforme ( le mot de apsse est maintenant initialisé a 0000) 

1. **Nouveau Compte:** Permet de créer un nouveau compte bancaire en saisissant les détails du client , qui sont  :
     -Le jour de l'ouverture du compte (jj/mm/aaaa)
     -Le numero du compte
     -Le nom du client
     -La date de naissance du client (jj/mm/aaaa)
     -l'age du client
     -L'adresse du client
     -Le numero de la carte d'identite du client
     -Le numero du telephone du client
     -Le montant à déposer
     -Le type du compte : #Compte d'Epargne
                          #Compte courant
                          #Compte fixe pour 1 ans
                          #Compte fixe pour 2 ans
                          #Compte fixe pour 3 ans

3. **Modifier Compte:** Permet de mettre à jour les informations d'un compte existant, telles que l'adresse ou le numéro de telephone.

4. **Consulter Compte:** Affiche les détails d'un compte particulier en saisissant le numéro de compte ou par nom du client .

5. **Supprimer Compte:** Supprime un compte existant en entrant son numéro de compte.

6. **Liste de Tous les Comptes:** Affiche la liste de tous les comptes enregistrés dans la banque.

7. **Somme Totale des Soldes:** Calcule et affiche la somme totale des soldes de tous les comptes actifs.

8. **Nombre Total de Comptes:** Affiche le nombre total de comptes clients enregistrés dans la banque.

9. **Transactions:** Afficher et gérer les transactions bancaires, il permet d'effectuer soit un depot ou un retrait en entrant le numero de compte .

10. **Quitter:** Permet de quitter le programme.

##Contribueur : Mohamed Lahiani

## Comment Utiliser

1. Compilez le programme en utilisant un compilateur C.

   ```bash
   gcc gestion_banque.c -o gestion_banque

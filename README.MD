# RFID Project

Ce projet permet de gérer le solde sur une carte RFID à l'aide d'un lecteur NFC et d'une interface utilisateur dans le terminal. Vous pouvez déposer, retirer, acheter des articles ou réinitialiser le solde de la carte.

## Prérequis

- Node.js (version 12 ou supérieure)
- npm (Node Package Manager)
- Un lecteur NFC compatible

## Installation

1. Clonez le dépôt ou téléchargez les fichiers du projet.
2. Installez les dépendances nécessaires en exécutant la commande suivante dans le répertoire du projet :

    ```sh
    npm install
    ```

## Utilisation

1. Connectez votre lecteur NFC à votre ordinateur.
2. Exécutez le script principal :

    ```sh
    npm start
    ```

3. Lorsque la carte est détectée, un menu s'affichera avec les options suivantes :
    - **Déposer** : Ajouter un montant spécifié au solde de la carte.
    - **Retirer** : Retirer un montant spécifié du solde de la carte.
    - **Acheter** : Acheter des articles (Coca, Orangina, Water) et déduire le montant correspondant du solde de la carte.
    - **Reset** : Réinitialiser le solde de la carte à zéro.

4. Suivez les instructions à l'écran pour effectuer les opérations souhaitées.

**Remarque** : Veuillez attendre 2-3 secondes après chaque opération pour permettre au lecteur NFC de traiter les données correctement.

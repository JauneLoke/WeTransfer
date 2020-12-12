# WeTransfer

> Durée du projet 3 jours en cours de formation

Création d'un service similaire à wetransfer.com en insistant sur le design et l'expérience utilisateur.
 
Créer une identité propre au service
Principe "keep it simple", UX minimaliste et efficace
Rédaction du mail en MJML.
 
        - une page avec un formulaire :
            - email de l'émetteur
            - email du destinataire
            - dossier, fichier à envoyer
            - bouton envoyer
 
        - une page intermédiaire :
            - enregistre les informations dans une base de données
            - enregistre le fichier dans un répertoire
            - envoi par mail en HTML le lien vers la page de téléchargement du fichier 
   
        - une page de résultat :
            - message de réussite
            - lien vers la page à copier/coller
 
        - une page permettant depuis l'ID enregistré dans la base de données, d’accéder au 
          téléchargement du fichier. le lien vers cette page est envoyé par mail

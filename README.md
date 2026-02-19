Cahier des Charges - Portfolio Professionnel
1. Présentation du Projet
Ce projet consiste en la création d'un portfolio numérique personnel. Il a pour but de présenter mon profil, mon parcours scolaire, ainsi que les missions effectuées lors de mon stage au sein du Groupe ESPI.
2. Objectifs
Visibilité : Présenter mon CV et mes compétences de manière moderne.
Traçabilité : Documenter les missions techniques réalisées en stage (matériel et programmation).
Contact : Permettre aux recruteurs ou partenaires de me contacter directement via un formulaire fonctionnel.
3. Spécifications Techniques
Technologies Utilisées
HTML5 : Structure sémantique du contenu.
Tailwind CSS (v4) : Framework CSS "Utility-First" pour un design responsive et moderne, incluant des effets de flou (backdrop-blur) et des dégradés complexes.
JavaScript (ES6) : Gestion de l'interactivité et de l'envoi du formulaire.
EmailJS : API tierce permettant l'envoi d'e-mails sans backend dédié.
Vercel : Plateforme de déploiement et d'hébergement.
Architecture du Code
Le code est organisé en sections distinctes pour une meilleure navigation :
Header : Menu de navigation fixe avec effet de flou et menu mobile intégré.
Hero Section : Présentation principale avec appel à l'action (Lien vers le CV).
Section "Qui je suis" : Résumé du profil professionnel.
Section "Parcours" : Chronologie de la formation (Lycée et Collège).
Section "Mon Stage" : Grille de cartes détaillant les missions (Programmation, Maintenance matériel).
Section "Organisation" : Utilisation d'un layout "Bento Grid" pour expliquer les méthodes de travail et les outils (GitHub, ChatGPT, Gemini).
Section "Équipe" : Organigramme interactif utilisant des fenêtres modales (<dialog>).
Section "Contact" : Formulaire dynamique relié à EmailJS.
4. Fonctionnalités Implémentées
Design Responsive : Le site s'adapte automatiquement aux écrans d'ordinateurs, tablettes et smartphones.
Navigation Fluide : Liens d'ancrage internes pour naviguer entre les sections.
Fenêtres Modales : Affichage de l'organigramme de l'entreprise via une boîte de dialogue interactive.
Gestionnaire d'Email :
Validation des champs obligatoires.
Retour visuel utilisateur ("Envoi en cours...", "Bravo !").
Réinitialisation automatique du formulaire après envoi.
5. Outils de Développement
Éditeur : VS Code.
IA Génératives : ChatGPT & Gemini (Aide à la structure et au débogage).
Versionnage : GitHub pour la sauvegarde et l'historique des modifications.
Quelques petits conseils pour ton GitHub :
Images : Assure-toi que ton dossier img/ est bien présent sur GitHub, sinon tes photos ne s'afficheront pas.
Sécurité : Pour un projet pro, on évite normalement de laisser les clés API en clair, mais pour un portfolio de stage, c'est tout à fait acceptable de montrer que tu sais configurer EmailJS !
Lien Vercel : N'oublie pas d'ajouter le lien de ton site dans la description "About" de ton dépôt GitHub.
 

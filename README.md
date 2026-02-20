# windows-arborescence-dossier
Explorateur interactif de la gestion des dossiers dans Windows, générée par Gemini et supervisé par Pierre-Olivier
Atelier Interactif : Arborescence de Fichiers
Cet outil pédagogique est conçu pour enseigner les concepts fondamentaux de la gestion de fichiers et de la structure de données en arbre. Il permet aux apprenants de manipuler visuellement des dossiers pour comprendre comment s'organise un système d'exploitation ou un projet web.

Accéder à l'outil
👉 https://prepapierreo.github.io/windows-arborescence-dossier/

🎯 Objectifs pédagogiques
Cette application permet de travailler les compétences suivantes :
Hiérarchie de données : Comprendre la relation "Parent/Enfant" dans une structure de dossiers.
Manipulation CRUD : Créer (Create), Renommer (Update) et Supprimer (Delete) des éléments.
Expérience Utilisateur (UX) : Utiliser le Glisser-Déposer (Drag & Drop) pour réorganiser des fichiers.
Algorithmique : Visualiser comment un changement de nom ou un déplacement affecte une branche entière.

🛠️ Fonctionnalités incluses
1. Gestion Interactive
Ajouter : Crée un sous-dossier à l'intérieur du dossier sélectionné.
Renommer : Modifiez le nom en temps réel via le champ de saisie (touche Entrée pour valider).
Glisser-Déposer : Déplacez n'importe quel dossier (et son contenu) vers un autre emplacement.
Toggle : Cliquez sur les flèches (▶/▼) pour réduire ou développer les branches.

2. Le Mode Défi (Challenge)
L'outil intègre un module de test !
Cliquez sur "Lancer le Mode Défi".
Une structure cible apparaît à gauche.
Vous devez reproduire exactement cette structure à droite.
Cliquez sur "Vérifier la solution" pour obtenir un feedback instantané.

🤖 Note sur la conception
Ce projet est un exemple de Single Page Application (SPA) développée sans framework (Vanilla JS).
Logique Récursive : Le code utilise des fonctions récursives pour parcourir l'arborescence, que ce soit pour le rendu visuel ou pour la vérification de la solution du défi.
État (State Management) : L'application maintient une structure JSON en mémoire qui représente l'état actuel du système de fichiers.

⚖️ Licence
Ce projet est sous Licence MIT. Il peut être librement utilisé, partagé et modifié par les apprenants et les formateurs.

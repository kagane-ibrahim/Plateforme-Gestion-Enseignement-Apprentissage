# Plateforme Moodle

## Présentation

Projet académique de plateforme éducative fondée sur Moodle. Les fonctionnalités présentées couvrent la gestion des utilisateurs, des cours, des quiz et de la base de données.

## Technologies

Moodle, PHP, MySQL, HTML, CSS, JavaScript et XAMPP.

## Présentation visuelle du projet

Les captures et diagrammes ci-dessous sont extraits du rapport du projet. Ils illustrent les interfaces et la conception, sans vérifier une instance Moodle en direct. Les adresses visibles dans la liste des utilisateurs et la note du quiz sont masquées dans les copies de publication ; les fichiers sources restent inchangés.

Le logo ci-dessous identifie la plateforme utilisée dans le projet.

![Logo Moodle](branding/moodle-logo.jpeg)

### Interface de connexion

Écran commun de connexion. Aucun rôle n’est déduit de cette vue.

![Écran de connexion Moodle](screenshots/commun/01-login-moodle.png)

## Interfaces Administrateur

### Tableau de bord

Vue du tableau de bord et de ses éléments de suivi.

![Tableau de bord administrateur](screenshots/admin/02-admin-dashboard.png)

### Gestion des utilisateurs et des rôles

Liste d’utilisateurs de l’administration ; les adresses de courriel sont masquées dans cette copie.

![Gestion des utilisateurs et des rôles](screenshots/admin/03-admin-users-and-roles.png)

## Interfaces Enseignant

### Vue des cours

Vue d’ensemble des cours associés à l’espace enseignant.

![Cours de l’enseignant](screenshots/enseignant/04-teacher-my-courses.png)

### Tableau de bord

Vue des blocs de chronologie et de calendrier du tableau de bord.

![Tableau de bord enseignant](screenshots/enseignant/05-teacher-dashboard.png)

### Contenu du cours Programmation Web

Sections, ressources et activités du cours Programmation Web.

![Contenu du cours Programmation Web](screenshots/enseignant/06-teacher-course-programmation-web.png)

### Gestion des questions du quiz

Liste des questions et options de gestion du quiz.

![Questions du quiz côté enseignant](screenshots/enseignant/07-teacher-quiz-questions.png)

### Gestion d’un devoir

Consignes et paramètres d’un devoir dans l’espace enseignant.

![Devoir côté enseignant](screenshots/enseignant/08-teacher-assignment.png)

### Forum du cours

Liste des discussions du forum d’un cours.

![Forum du cours côté enseignant](screenshots/enseignant/09-course-forum.png)

## Interfaces Étudiant

### Tableau de bord

Vue des blocs de chronologie et de calendrier dans l’espace étudiant.

![Tableau de bord étudiant](screenshots/etudiant/10-student-dashboard.png)

### Vue des cours

Cours présentés sous forme de cartes dans l’espace étudiant.

![Cours de l’étudiant](screenshots/etudiant/11-student-my-courses.png)

### Résultat du quiz

Consultation d’un quiz et de ses tentatives ; la note est masquée dans cette copie.

![Résultat du quiz côté étudiant, note masquée](screenshots/etudiant/12-student-quiz.png)

### Devoir à remettre

Consigne du devoir et état de remise visible dans l’interface.

![Devoir côté étudiant](screenshots/etudiant/13-student-assignment.png)

### Forum du cours

Consultation d’une discussion dans le forum du cours.

![Forum du cours côté étudiant](screenshots/etudiant/14-student-course-forum.png)

## Conception et diagrammes

### MCD — Modèle conceptuel de données

Représentation conceptuelle des entités du projet et de leurs relations.

![Modèle conceptuel de données](diagrams/01-mcd.png)

### MLD — Modèle logique de données

Traduction relationnelle du modèle avec les clés primaires et étrangères représentées.

![Modèle logique de données](diagrams/02-mld.png)

### Organisation des rôles

Résumé des rôles et de leurs principales interactions dans la plateforme.

![Schéma d’organisation des rôles administrateur, enseignant et étudiant](diagrams/03-role-organization.png)

### Diagramme UML de cas d’utilisation

Fonctions principales associées aux rôles administrateur, enseignant et étudiant.

![Diagramme UML de cas d’utilisation](diagrams/04-use-case.png)

### Diagramme UML de séquence

Échanges entre les rôles et le système pour des opérations pédagogiques.

![Diagramme UML de séquence](diagrams/05-sequence-diagram.png)

### Diagramme UML de classes

Classes principales et relations représentées dans le modèle.

![Diagramme UML de classes](diagrams/06-class-diagram.png)

### Diagramme UML d’activité

Enchaînement simplifié des étapes de gestion et de suivi d’un cours.

![Diagramme UML d’activité](diagrams/07-activity-diagram.png)

## Cadre

Projet académique. Cette page résume les informations disponibles, ne revendique pas d’expérience professionnelle et n’ajoute pas de fonctionnalités au-delà de celles communiquées.

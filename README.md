# live-code-editor
les tables

----------modules
----------semaine
----------tests
----------questions
----------commentaire
----------solutions





table-> module->
-titre
-description
-image
-statut
-date_ajout
-date_update



table-> semaine->
-nom_semaine
-module_id
-date_ajout
-date_update
-statut



table->tests->
-titre
-semaine-id
-question_id
-date_ajout
-date_update
-statut



table->questions->
-titre
-user_id
-nombre_quest
-date_ajout
-date_update
-satut



table->reponse->
-test_id



table->commentaire->
-user_id
-test_id
-statut
-date_ajout
-message



table->resultat->
-reponse_id
-user_id
-test_id



table->reponse->
-test_id
-user-id
-question_id

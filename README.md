# live-code-editor
les tables

----------modules
----------semaine
----------tests
----------questions
----------resultat






table-> module->
***titre
***langage
***statut
***date_ajout
***date_update



table-> semaine->
***numero_semaine
***titre
***debut
***fin
***module_id
***date_ajout
***date_update
***statut



table->tests->
***titre
***semaine-id
***nombre_question
***date_ajout
***date_update
***statut



table->questions->
***titre
***description
***date_ajout
***date_update
***user_id
***test_id
***satut



table->resultat->
***user_id
***question_id
***resultat_reponse




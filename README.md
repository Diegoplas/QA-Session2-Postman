#Commands needed to excecute automatically the tests usign the CLI from inside the Project folder "QA-Postman":

	$ newman run './QA-Postman/collection/Todoist.postman_collection.json' -e './QA-Postman/envVariables/QA2.postman_environment.json' -r htmlextra --reporter-htmlextra-export './QA-Postman/reports/reporte.html'
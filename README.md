## Commands needed to execute the tests automatically using the CLI from inside the project folder "QA-Postman"

```bash
newman run './QA-Postman/collection/Todoist.postman_collection.json' -e './QA-Postman/envVariables/QA2.postman_environment.json' -r htmlextra --reporter-htmlextra-export './QA-Postman/reports/reporte.html'
```

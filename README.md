# jmixpm-flow-base
Base Jmix Flow project with project management data model

This project contains:
- Data model with Project, Task, TimeEntry, ProjectStatus, and User entities
- TaskService - service that returns least busy User
- List and Detail views for JPA entities
- Liquibase changelogs for init and fill data model - 3 Users, 2 Projects with 3 Tasks in each (6 Tasks in total)

Project may be used as a basic Flow project for trainings:

* Security basic
* Working with data basic
* UI basic
* Working with files in Jmix
* Using Jmix Studio efficiently
* Advanced deployment
* Emailing in Jmix
* Testing Jmix applications

docker run -e VAULT_DEV_ROOT_TOKEN_ID=myroot -p 8200:8200 hashicorp/vault

Kubernetes code added to the folder k8s

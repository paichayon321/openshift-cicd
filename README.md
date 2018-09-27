# openshift-cicd
SonarQube with Embedded H2 Database:

oc new-app -f sonarqube-template.yaml --param=SONARQUBE_VERSION=7.0

SonarQube with PostgreSQL Database:

oc new-app -f sonarqube-postgresql-template.yaml --param=SONARQUBE_VERSION=7.0


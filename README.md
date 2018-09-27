# openshift-cicd
SonarQube with Embedded H2 Database:

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/sonarqube-template.yaml --param=SONARQUBE_VERSION=7.0

SonarQube with PostgreSQL Database:

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/sonarqube-postgresql-template.yaml --param=SONARQUBE_VERSION=7.0


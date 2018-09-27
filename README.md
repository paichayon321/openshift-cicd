# openshift-cicd
#Jenkins with persistent

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/jenkins-persistent.yaml

#Jenkins without persistent

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/jenkins-ephemeral.yaml

#SonarQube with Embedded H2 Database:

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/sonarqube-template.yaml --param=SONARQUBE_VERSION=7.0

#SonarQube with PostgreSQL Database:

oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/sonarqube-postgresql-template.yaml --param=SONARQUBE_VERSION=7.0

#Gogs with persistent
oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/gogs-persistent-template.yaml --param=GOGS_VERSION=0.11.34

#Gogs without persistent
oc new-app -f https://raw.githubusercontent.com/paichayon321/openshift-cicd/master/gogs-template.yaml --param=GOGS_VERSION=0.11.34





$ oc new-app wildfly:latest~. --name mywar

$ oc start-build mywar --from-file=sample.war

$ oc expose svc mywar

$ oc get route

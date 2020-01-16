# D288-ch04-01-java-serverhost

importar image builder:

oc import-image openjdk18 --from=registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift --confirm  tags=builder 

oc new-app --name jhost -i openjdk18 https://github.com/searva/D288-ch04-01-java-serverhost.git


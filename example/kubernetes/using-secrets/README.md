# Generating ldap-secret.yaml

`make example`

Then edit the yaml files in the environment directory to have the desired paraneters, and then make the secret file:

`make ldap-secret.yaml`

And deploy the secret you just made:

`kubectl apply -f ldap-secret.yaml`

Apply the deployment yaml for ldap in k8s:

`kubectl apply -f ldap-deployment.yaml`

Finally apply the service yaml for ldap in k8s:

`kubectl apply -f ldap-deployment.yaml`

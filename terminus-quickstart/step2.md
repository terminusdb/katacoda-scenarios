## Step 2: Configure with Environment Variabls

You can use enviroment variables to change the scipts settings


### Set Server host

Set the server host to this tutorial container

`export TERMINUS_SERVER="[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com"`{{execute}}

### Set Server port to 80

Set the http port to 80 to that the console can access via the ingress

`export TERMINUS_PORT=80`{{execute}}

### Set Desired TerminusDB Server Version

Set the version to v1.1.1

`export TERMINUS_TAG=v1.1.1`{{execute}}

### Set Server API Key

Set a server password

`export TERMINUS_PASS="escapable customary cosigner vertigo"`{{execute}}


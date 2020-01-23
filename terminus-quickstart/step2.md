## Step 2: Configure with Environment Variables

You can use enviroment variables to change the scipts settings


### Set Server host

Set the server host to this tutorial container

`export TERMINUS_SERVER="[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com"`{{execute}}

### Set Public URL

Set the public url by which this host is reachable from the internet

`export TERMINUS_PUBLIC_URL="https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com"`{{execute}}

### Set Server port to 80

Set the http port to 80 to that the console can access via the ingres

`export TERMINUS_PORT=80`{{execute}}

### Set Server API Key

Set a server password

`export TERMINUS_PASS="escapable customary cosigner vertigo"`{{execute}}


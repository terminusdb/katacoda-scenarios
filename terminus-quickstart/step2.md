## Step 2: Configure with Environment Variabls

You can use enviroment variables to change the scipts settings

### Set Desired TerminusDB Server Version

Set the version to v1.1.1

`export TERMINUS_TAG=v1.1.1`{{execute}}

### Set Server name to this Container

Set the server name to be the automatically generated name of this turorial
container.

`export SERVER_NAME=[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com`{{execute}}

### Set Web Console Port

Set the port to the standard https port 443

`export TERMINUS_PORT=443`{{execute}}

### Set Web Console to Use https

Set the the web protol to https

`export TERMINUS_SCHEME=https`{{execute}}

### Set Server API Key

Set a server password

`export TERMINUS_PASS="escapable customary cosigner vertigo"`{{execute}}


# WikiPagesWatcher
A Node application to monitor the Wikimedia Foundation's 2017 Community Wishlist Survey.

## Installation ##
* `npm install`
* `cp credentials.json.dist credentials.json` then modify it accordingly.

## Usage ##

### Local ###
Use `node patrol.js` to see the live feed, or `nohup node patrol.js &` to run it in the background.

### Toolforge ###
`kubectl create -f /data/project/community-tech-tools/SurveyCop/deployment.yaml`

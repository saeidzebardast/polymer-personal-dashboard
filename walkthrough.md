# Walkthrough

This file shows the steps of creating personal dashbboard project from scratch.

# Prerequisites

* install [git](https://git-scm.com/downloads)
* install [nodejs](https://nodejs.org/en/download/)
* ```npm install -g bower```
* ```npm install -g polymer-cli```

# Setup project

Create empty Polymer project with [app-drawer-template](https://github.com/Polymer/app-drawer-template):

* ```mkdir polymer-personal-dashboard```
* ```cd polymer-personal-dashboard```
* ```polymer init app-drawer-template```

# Required Elements

We need to use some web components to enrich our dashboard:

## [&lt;moment-js&gt;](https://github.com/saeidzebardast/moment-js)

* ```bower install --save moment-js```
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

# Create Elements and Pages

## Home Page

### Third Party Elements

#### [&lt;moment-js&gt;](https://github.com/saeidzebardast/moment-js)
```bower install --save moment-js```

## Tasks Page

### Elements

#### &lt;ppd-task&gt;
```mkdir -p src/elements/ppd-task/ && touch src/elements/ppd-task/ppd-task.html```

### Third Party Elements

#### [&lt;paper-input&gt;](https://elements.polymer-project.org/elements/paper-input)
```bower install --save PolymerElements/paper-input```

#### [&lt;paper-item&gt;](https://elements.polymer-project.org/elements/paper-item)
```bower install --save PolymerElements/paper-item```

#### [&lt;paper-checkbox&gt;](https://elements.polymer-project.org/elements/paper-checkbox)
```bower install --save PolymerElements/paper-checkbox```

#### [&lt;paper-toast&gt;](https://elements.polymer-project.org/elements/paper-toast)
```bower install --save PolymerElements/paper-toast```

## Calculator Page

### Third Party Elements

#### [&lt;paper-button&gt;](https://elements.polymer-project.org/elements/paper-button)
```bower install --save PolymerElements/paper-button```

#### [&lt;iron-flex-layout&gt;](https://elements.polymer-project.org/elements/iron-flex-layout)
```bower install --save PolymerElements/iron-flex-layout```

#### [&lt;paper-styles&gt;](https://elements.polymer-project.org/elements/paper-styles)
```bower install --save PolymerElements/paper-styles```

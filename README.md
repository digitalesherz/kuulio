# KUUL.IO
## Modules

### Set up HARP.JS
```BASH
sudo npm install -g harp
```

### Install Browsersync.js
```BASH
npm install -g browser-sync
```

## Start Development
```BASH
harp server --port 9000
&
browser-sync start --proxy 'localhost:9000' --files '**/*.jade, **/*.md, **/*.less'
```
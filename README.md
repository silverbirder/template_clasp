# template_clasp
This repository is the boiler template that develop with clasp

## Setup

```
$ npm install -D
$ npm run login
$ npm run init
$ rm appscript.json
$ sed -e 's/}/, "rootDir": ".\/dist"}/g' .clasp.json > t && mv t .clasp.json
```

## Dev
```
$ npm run build
$ npm run push
$ npm run test
```
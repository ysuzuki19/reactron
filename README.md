# reactron
React + Electron boiler plate

# react
create react project with `create-react-app`

# START ON LINUX
run electron app for developing.

```bash
$ git clone https://github.com/ysuzuki19/reactron
$ cd reactron
$ npm install
$ npm run electron
```

if you want to run on browser, 

```bash
$ npm start
```

# BUILD ON LINUX

```bash
$ npm run build-linux     # build linux only
$ npm run build-mac       # build mac   only
$ npm run build-win       # build win   only
$ npm run build-all       # build linux/mac/win
```

# FOR MAC USER
Please remove following line in `package.json`.

```json
"target": "tar.gz"
```


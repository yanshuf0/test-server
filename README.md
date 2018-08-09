# test-server
small test server for angular apps

## build
1. `npm install`
2. put `dist` folder in root dir.
3. add a `settings.json` with a JSON object like this: `{"apiRoot": "portofyourapiroot"}` in the `dist` folder.
4. `node ./index.js`

When recompiling you can do something like: `rm -r dist && cp -r <pathToDist>/dist ./dist && cp settings.json ./dist/
&& node index.js` if you have a `settings.json` in the root dir.

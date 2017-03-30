### FullStack TypeScript, React starter kit.

---


##### What's included
* TypeScript
* React
* React router v4

##### Usage:
* `npm run dev` - Server and client are in watch mode with source maps
* `npm run build` - `dist` folder will include all the needed files, both client (Bundle) and server.
* `npm start` - Just runs `node ./dist/server`  

##### Notes:
* Separated `tsconfig.json` for server and client.
* Server is emitted by TypeScript, client is bundled using Webpack.
* Server can client can share code (And types). For example: Validation.ts, IUserDTO.d.ts

---

##### Client Tree
##### Server Tree

---

##### What's not included
* Universal
* Redux [How to add]
* Styling library [How to add]

##### Requirements
* Node 6.9.5+




---
### todo
* More docs
* example for shared code
* tslint? (Only on pre-commit?)
* minify on build?
 
* client
  * call the server api
  * static files
  * use tslib
  * polyfills? (For Object.assign and Promise)
  
* server
  * Currently is using static html, let webpack generate the html out of a template
  * The server is is using /dist/public, for statics... what can we do here?
  * favicon
  * refresh the browser after server compilation success

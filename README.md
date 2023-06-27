# Typescript Examples

Example code for by [blog posts on Typescript](https://sohamkamani.com/typescript/).

Each example is contained within its own folder.

To run any example:

1. Clone this repository
2. Run `npm install` 

**For web-based examples** (where there is an `index.html` file in the example folder - [like this](./rest-http-api-call)):

1. Run `npx tsc <folder-name>/index.ts --watch --inlineSourceMap --target es2016`. 
2. Start an http server by running `npx http-server`.
3. Then you can open the `index.html` fie in your browser on `localhost:8080/<folder-name>/index.html`.

**For nodejs-based examples** run `npx ts-node <folder-name>/index.ts`.

  
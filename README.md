# assignment14

# Step 1:- Install/Update node.js to version 8.9.x or above
# Step 2:- run the command to install LoopBack 4 
```sh
npm install -g @loopback/cli
```
# Step 3:- create a new project using the code
```sh
lb4 app
```            
# Step 4:- Answer the prompt accordingly
# Step 5:- Start the project using  
```sh
cd getting-started 
npm start
```            
# Step 6:- Add a controller using 
```sh
lb4 controller
```
# Step 7:- Answer the promt accordingly 

I had created a hello controller which displays Hello World! message 

# Step 8:- Update the controller with the appropriate code 

I had used the code below

```sh
import {get} from '@loopback/rest';
export class HelloController {
@get('/hello')
hello(): string {
return 'Hello world!';
}
}
```
# Step 9:- Start the Project using
```sh
npm start
```              
This application is generated using [LoopBack 4 CLI](https://loopback.io/doc/en/lb4/Command-line-interface.html) with the
[initial project layout](https://loopback.io/doc/en/lb4/Loopback-application-layout.html).

## Install dependencies

By default, dependencies were installed when this application was generated.
Whenever dependencies in `package.json` are changed, run the following command:

```sh
npm install
```

To only install resolved dependencies in `package-lock.json`:

```sh
npm ci
```

## Run the application

```sh
npm start
```

You can also run `node .` to skip the build step.

Open http://127.0.0.1:3000 in your browser.

## Rebuild the project

To incrementally build the project:

```sh
npm run build
```

To force a full build by cleaning up cached artifacts:

```sh
npm run rebuild
```

## Fix code style and formatting issues

```sh
npm run lint
```

To automatically fix such issues:

```sh
npm run lint:fix
```

## Other useful commands

- `npm run migrate`: Migrate database schemas for models
- `npm run openapi-spec`: Generate OpenAPI spec into a file
- `npm run docker:build`: Build a Docker image for this application
- `npm run docker:run`: Run this application inside a Docker container

## Tests

```sh
npm test
```

## What's next

Please check out [LoopBack 4 documentation](https://loopback.io/doc/en/lb4/) to
understand how you can continue to add features to this application.

[![LoopBack](https://github.com/loopbackio/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png)](http://loopback.io/)

# hackernews

This project is a simple Api Call by `TypeScript, GraphQL, Apollo Server, Nexus`.

## Features

- Made with TypeScript
- Creating HTTP web server by Apollo Server.
- Generation GraphQL schema by Nexus.

## Sending authenticated requests

Some endpoints are restricted to authenticated users only.
To send an authenticated request, add `Bearer Token` header to request headers with a valid session token.

## Getting Started

### Creating the project
``
    git clone https://github.com/ckymn/hackernews-typescript-graphql.git
    cd hackernews-typescript
    npm init -y
``

### Installing and configuring TypeScript
``
    npm install --save-dev typescript@^4.3.5 ts-node-dev@^1.1.8
    touch tsconfig.json              
``

### Creating tsconfig.json [ ../hackernews-typescript-graphql/tsconfig.json ]
```json
    {
      "compilerOptions": {
        "target": "ES2018",
        "module": "commonjs",
        "lib": [
          "esnext"
        ],
        "strict": true,
        "rootDir": ".",
        "outDir": "dist",
        "sourceMap": true,
        "esModuleInterop": true
      }
    }            
```

### Creating server 
``
    npm install apollo-server@^3.1.1 graphql@^15.5.1 nexus@^1.1.0          
``


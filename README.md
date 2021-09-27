<h1 align="center">
<img width="40" valign="bottom" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1024px-Typescript_logo_2020.svg.png">
Docker + Node 16 + TypeScript 4 + Express 4 Starter
</h1>
<h4 align="center">A minimal Docker project to write Node/Express apps in TypeScript.</h4>
<br/>
<h2>Installation</h2>

```
npm install
```

<h2>Usage</h2>

Start express server in dev mode (hot reloading):

```
npm run serve
```

Start express server in production mode:

```
npm run start
```

Run the server in a docker container:

```
docker compose up
```

The server is accessible at http://localhost:8081

Docker uses the official [Node 16](https://github.com/nodejs/docker-node) image based on Alpine Linux.

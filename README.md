# Project Heartcode 2020

> A community service project organised by Singapore Management University, School of
> Information Systems. Project HeartCode serves to provide less privileged youths the
> opportunity to explore their interest in IT through solving real world problems with IT
> innovations.

In Dec 2020, I was the web trainer for SMU HeartCode 2020. This website contains the
remanences of a multi module repo of systems that teach basic web programing with HTML,
CSS, JavaScript facilitated through the use of Vue.js + Nuxt.js.

### Previously Mono Repo

Prior to converting this project into a static site generated website it contains 5
modules.

- heartcode.app: The website that contains the course material.
- serve: Front proxy to serve student projects and route all traffic.
- api.heartcode.app: CLI endpoint for the student to deploy their code.
- heartcode-web-dev: Nuxt.js template with materials of the workshop.
- create-heartcode-web-dev: Create `heartcode-web-dev` environment in seconds.

### Development

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

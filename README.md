<p align="center">
  <h1> Sunrise </h1>
</p>

[Sunrise](https://amplication.com/) is an open‑source development platform. It helps professional Node.js developers build quality Node.js applications without spending time on repetitive coding tasks.

Sunrise auto-generates backend apps built with TypeScript and Node.js, and a client built with React.

# Features

Amplication provides the following features:

- Production-ready APIs
- Data Model
- Role Based Access Control
- Microservice Support
- Continuous GitHub Sync
- TypeScript and Node.js Source Code
- Plugin System
- Monorepo or Polyrepo
- Custom Code
- Ready-to-deploy-app
- Admin UI
- Amplication console & CLI

# Requirements

You can get started with Amplication immediately on the Amplication Cloud. 

Alternatively you can set up a local development environment.


## Tutorials 

- Todo Application using Amplication and Angular. [Click here to access](https://docs.amplication.com/docs/tutorials/angular-todos/)
- Todo Application using Amplication and React. [Click here to access](https://docs.amplication.com/docs/tutorials/react-todos/)

## Amplication Cloud (SaaS)

Launch Amplication from [app.amplication.com](http://app.amplication.com/)

## Development Environment (Local)

### System Requirements

:bulb: Before you begin, make sure you have the following installed:

- [Node.js v16 or above](https://nodejs.org/en/download/)
- [Docker](https://docs.docker.com/desktop/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git/)


### Initializing all the packages

Amplication is using a monorepo with multiple packages. To initialize all the packages on a local development environment, including running a docker image for the DB and seeding the DB.

1. Execute the following commands in the project root folder:

```jsx
npm install
npm run setup:dev
```
This will install all the required dependencies, run the necessary scripts and init a Docker-based Postgres server.

2. Go to `.../packages/amplication-server` and execute the following command:

```jsx
npm run start
```

3. Go to `.../packages/amplication-client` and execute the following command:

```jsx
npm run start
```




### Setting Up Amplication Manually

You can use a manual step-by-step approach to set up Amplication in a local development environment. To do so, you should follow the following instructions for **Setting Up Amplication Server**, and **Setting Up Amplication Client**.

#### Setting up [Amplication Server](https://github.com/amplication/amplication/blob/master/packages/amplication-server/README.md)

Amplication Server is the main component of the platform that provides all the core functionality to design and create low-code applications.
The server exposes a GraphQL API for all actions. The server is built with the following awesome open-source technologies: Node.js, NestJS, Prisma over PostgreSQL, GraphQL API, and many more...

#### Setting Up [Amplication Client](https://github.com/amplication/amplication/blob/master/packages/amplication-client/README.md)

Amplication Client is the front end of the platform that provides you with an easy-to-drive UI for building your next low-code application.
The client is based on React, Apollo client, Primer components, React Material Web Components, Formik, and more.

# Version 1

Amplication is currently in its version 1.  This is the first major release of Amplication with enterprise-grade production readiness & scale. In this version, we have introduced multiple new features and enhanced the existing ones. The feature set is listed above in the [Features](#features) section.

## Support

Ask your questions and participate in discussions on Amplication-related and web-dev topics at the Amplication Discord channel. 

<a href="https://discord.gg/Z2CG3rUFnu"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

## Create a bug report

If you see an error message or run into an issue, please [create bug report](https://github.com/amplication/amplication/issues/new?assignees=&labels=type%3A+bug&template=bug.yaml&title=%F0%9F%90%9B+Bug+Report%3A+). This effort is valued and helps all Amplication users.


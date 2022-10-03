[![Starware](https://img.shields.io/badge/⭐-Starware-f5a91a?labelColor=black)](https://github.com/zepfietje/starware)

<p align="center">
  <img src="logo.png">
</p>
<h1 align="center">Journal Policy Tracker: Backend</h1>

### This is the backend repository for the [Journal Policy Tracker](https://github.com/codeisscience/codecompliance-frontend) web application.

### Database Schema Design for the Journal Policy Tracker can be found [here](https://github.com/codeisscience/code-is-science/issues/62#issuecomment-686518507)

## Tech Stack used

- [Express](https://expressjs.com/)
- [GraphQL](https://graphql.org/)
- [Apollo GraphQL Server](https://www.apollographql.com/docs/apollo-server/)
- [Mongoose](https://mongoosejs.com/)
- [Mongo DB](https://www.mongodb.com/)
- [Babel](https://babeljs.io/)
- [GitHub Actions](https://docs.github.com/en/actions)
- [Docker](https://www.docker.com/)
- [DigitalOcean](https://www.digitalocean.com/)

## Local Environment Setup

---

### Prerequisites

- [MongoDB](https://www.mongodb.com/try/download/community) 5.0 or newer.
- [Redis](https://redis.io/download/) - It is available only for Linux and Mac so if you are using windows then try using [this](https://github.com/tporadowski/redis) version of Redis.

Create an `.env` file in the root folder and paste the following into it.

```
DATABASE_URL=mongodb://localhost:27017/testMongo
PORT=4000
SESSION_SECRET=asdilkhudfgaiosuvbiapsdi
```

### Installing dependencies

```console
$ yarn install
```

### Running

To run Apollo Server:

```console
$ yarn start
```

To run all the tests for the server:

```console
$ yarn test
```

> These commands and values in the `.env` file will change after the deployment of the app so check back if they are not working anymore. If you are facing any problems while setting up this project locally then feel free to create an issue.

## Contribute to this project

---

Our Slack Community: [Slack Invite](https://join.slack.com/t/codeisscience/shared_invite/zt-16g3i8hr7-6j~jd_6JddhjEUBq9YUkmQ)

`Contributions are welcome 🎉🎉`

Please refer to the project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

1. **Fork** the repo on GitHub
2. **Clone** the project to your own machine
3. **Commit** changes to your own branch
4. **Push** your work back up to your fork
5. Submit a **Pull request** so that we can review your changes

NOTE 1: Please abide by the [Contributing Guidelines](./CONTRIBUTING.md).

NOTE 2: Please abide by the [Code of Conduct](./CODE_OF_CONDUCT.md).

## Starware

---

This project is Starware.  
This means you're free to use the project, as long as you star its GitHub repository.  
Your appreciation makes us grow and glow up. ⭐

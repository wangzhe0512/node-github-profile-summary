# node-github-profile-summary

<p align="center">
  <img src="https://user-images.githubusercontent.com/12621342/35959365-41f352b0-0ce0-11e8-8a5b-05ad054ea378.png">
</p>

> The node version of github-profile-summary which is inspired by tipsy' [github-profile-summary](https://github.com/tipsy/github-profile-summary)

Site: https://gh-profile-summary.teamsz.xyz

## Major skills or tools:

- Vue
- Chart.js
- Koa
- Github graphql api
- now.sh

## Screenshot

### Cool & beautiful profile list

![](https://user-images.githubusercontent.com/12621342/35951697-89e3338e-0cb7-11e8-9986-dc258f257b97.png)

### Share system & Save your profile as Image

![](https://user-images.githubusercontent.com/12621342/35951773-d1c9cf50-0cb7-11e8-80b2-08ae7d876533.png)

## Local run

> You need to have node environment!

### Install

``` bash
git clone https://github.com/Molunerfinn/node-github-profile-summary.git
cd node-github-profile-summary
npm install # or yarn
```

### Setup

First generate a token at https://github.com/settings/tokens

Then You need to create a `.env` file in the project folder.

The `.env` file looks like:

```env
GH_TOKEN=Your token here
JWT_SECRET=Any string
KOA_PORT=8888
HTTPS=false
```

> KOA_PORT can be any port you like which is available.

**If you set `HTTPS=true`, then the websocket will connect the 443 port, it's useful for https production.**

### Run

```bash
npm run build
npm start
```

And then open the link `http://localhost:8888`, Done.

## TODOS

- More useful charts
- Docker support
- ...


## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018 Molunerfinn



# V2Ray Heroku

## Overview

Used to deploy V2Ray Websocket on Heroku.

**Heroku provides us with a free container service, we should not abuse it, so this project should not be used as a long-term use. **

**You can deploy more than two applications to achieve [Load Balancing](https://toutyrater.github.io/app/balance.html) to avoid a long-term high-traffic connection to a certain application and be judged as abuse by Heroku. **

**Heroku's network is not stable, please think twice before deploying. **

## Mirror

This image will not be blocked because it takes up a lot of resources.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Flaintuv00%2Fv2ray-heroku)

## ENV settings

### UUID

`UUID`> `A UUID for the user to authenticate when connecting.`

## Note

The WebSocket path is `/`.

`alterId` is `64`.

V2Ray will automatically install the latest version during deployment.

**For security reasons, unless you use a CDN, please do not use a custom domain name. Instead, use the secondary domain name assigned by Heroku to achieve V2Ray Websocket + TLS. **

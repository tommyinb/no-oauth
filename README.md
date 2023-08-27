# No OAuth

Just point your resource server to our authorization server.

Our authorization server will brainlessly accept all OAuth requests.

> https://no-oauth.onrender.com

## Endpoints

According to OAuth, you will need the following essential endpoints.

| path   | usage                                 |
| ------ | ------------------------------------- |
| /auth  | grants access by just a click         |
| /token | gives out access token without asking |
| /      | counts requests                       |

## Development

Of course, you can also run the authorization server in your own environment.

    node index.js

## Disclaimer

Remember to switch to a real OAuth provider before launching your project.

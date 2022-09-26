# Team Dev Sim - API Spec

## Getting Started

1. You can view the API Spec [here](https://hubertlemczak.github.io/team-dev-api/)
2. Run your [team dev server](https://github.com/boolean-uk/team-dev-server) on `http://localhost:4000`
3. Register a user account via the `/user Create user` endpoint. You can send a request by clicking the `Try it out` button on the right hand side and then `Execute` after you entered your details.
4. If the request is successful you can login with your email and password via the `/login` endpoint.
5. Copy your Bearer `token` and paste it into the `Authorize` field at the top of the page, or by clicking on the padlock on one of the protected endpoints.
6. After the token is authorized you will notice the padlocks become `locked` and you can now access the other protected endpoints.

Note that your Bearer token may not have access to all endpoints.

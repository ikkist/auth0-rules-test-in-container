# What is it?

The _auth0-rules-test-in-container_ library demonstrates using the [auth0-rules-local-testharness](https://github.com/auth0/auth0-rules-local-testharness) library to unit test rules in a local dev or CI environment without the need to run them in an actual webtask environment. This example runs the rules testing in a Docker Container.

See here for further documentation on [Auth0 Rules](https://auth0.com/docs/rules).

And here for using Docker: [Use Docker to Create a Node Development Environment](https://auth0.com/blog/use-docker-to-create-a-node-development-environment/?utm_source=dev&utm_medium=sc&utm_campaign=docker_devenv)

## Prerequisites

A Docker account, free tier is fine.

[Install Docker](https://www.docker.com/products/docker-desktop)

## Running Tests

This example has a few sample rules in the **example rules** folder and sample tests in the **tests** folder. To run the tests simply execute

```
npm run dockerTest
```

## What is Auth0?

Auth0 helps you to:

- Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
- Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
- Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
- Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
- Analytics of how, when and where users are logging in.
- Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 Account

1. Go to [Auth0](https://auth0.com/signup) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.

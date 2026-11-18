# AutoSDET

  Open-source backend services you configure, not rewrite.

  Every AutoSDET service is switched on and shaped by configuration, covered by black-box tests that run the real Docker
  image, and documented end to end. Use it as a ready-made microservice, or embed it in your own Spring Boot app.

  [Website](https://autosdet.com) · [Documentation](https://autosdet.com/docs) · [Auth Initializr](https://autosdet.com/auth/initializr)

  ## Products

  ### Auth Service

  Authentication and authorization for your apps: run it as a standalone service, or add one dependency to a Spring Boot
  app.

  - Registration and login by email, username or phone, with email and phone verification
  - JWT access tokens with rotating refresh tokens, sessions and logout from every device
  - Multi-factor authentication (authenticator apps, email, SMS, recovery codes) and passwordless login
  - Social login with Google, Microsoft, Apple, GitHub or any OpenID Connect provider
  - Roles and permissions, API keys, machine-to-machine clients and an admin API
  - Multi-tenancy, webhooks, audit log, rate limits and account lockout
  - Its own OpenID Connect provider, so other apps can offer "Sign in with" your service
  - PostgreSQL or MySQL, Java 25 and Spring Boot 4

  Start in the browser with the [Auth Initializr](https://autosdet.com/auth/initializr): pick the features you need, and
  download a ready-to-run Docker setup or a Maven or Gradle project.

  ### More to come

  Auth Service is the first product. New services follow the same idea: configure, don't rewrite.

  ## Principles

  | Principle | What it means |
  | --- | --- |
  | Configuration over code | Every feature sits behind a setting with a secure default, so you turn it on instead of writing it |
  | Tested like a user | Black-box suites test the published Docker image over HTTP, on every supported database |
  | Documented end to end | Guides for every feature, an API reference with real responses, and a Postman collection |
  | Open source | Apache License 2.0 |

  ## Contributing and security

  Issues and pull requests are welcome. Please report vulnerabilities privately through GitHub's security advisories, as
  described in each repository's `SECURITY.md`, never in a public issue.

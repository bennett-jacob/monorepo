# `secrets`

`/secrets/` contains encrypted secrets for the monorepo. Each secret (or directory of secrets) should contain an accompanying README that explains what the secret is and how it should be used.

Secrets are often used in build pipelines, but they can also be used in development environments. For example, a secret might contain a private API key that is used to access a third-party service.

_This directory should not be imported by other directories._

# Example service account

This is an example service account file (from [Google Cloud IAM](https://cloud.google.com/iam/docs/creating-managing-service-account-keys)). It's encrypted using `gpg`.

## How to decrypt

```sh
gpg -d secrets/example-service-account.json.gpg > secrets/example-service-account.json
```

Normally we wouldn't add the password to the codebase. But to show this example, here's the password to decrypt this file:

```text
3rmZzKGZcB5XGYPZcBAJu9oWHaEkS7
```

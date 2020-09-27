# @proficonf/eslint-config

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files. Instead of using a file path for the value of extends, use your module name. For example:

```json
{
    "extends": "@proficonf/eslint-config"
}
```

You can also omit the `eslint-config` and it will be automatically assumed by ESLint:

```json
{
    "extends": "@proficonf"
}
```

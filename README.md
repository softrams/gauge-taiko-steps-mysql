# Gauge Taiko Steps for MySQL

Implements gauge steps for interacting with MySQL Database, so that tests can be directly written without having to implement
steps for most common scenarios.

This is built as a sample and include some basic data integrity checks. Need to enhance to include most common scenarios.

## How to use it

Installl this npm package to your Gauge js project. And update STEP_IMPL_DIR in ./env/default/js.properties to include
steps implemenation from this package.

```bash
STEP_IMPL_DIR = tests,node_modules/@softrams/gauge-taiko-steps-mysql/lib
```

Setup Database Credentials as environment variables or in properties file (./env/default/default.properties)

```bash
export DB_HOST=
export DB_USER=
export DB_PASSWORD=
export DB_DATABASE=
```

And that's it. Start writing tests.

## Thanks to these amazing projects

- Gauge Framework (https://gauge.org/)
- Taiko (https://taiko.dev/)

# flask_kv_api

![Tests status](https://github.com/still-coding/flask_kv_api/actions/workflows/python-test.yml/badge.svg?branch=mongodb)

A tiny Flask REST API for key-value storage. **MongoDB branch**.

You can switch between branches to change key-value storage flavour.

## Quick start

Deploy containers using:

```shell
docker compose up
```

Go to http://localhost:8080/ to fiddle with Swagger UI.

Go to http://localhost:8080/keys_page/ to see all current keys and values.

Go to http://localhost:8081/ to enter Mongo Express.
# LiteStream Docker-Compose BoilerPlate

This is an example setup using [litestream](https://github.com/benbjohnson/litestream) connecting to a minio S3 compatible storage.

## Quick Start

- You can run ```make up``` to start up the docker setup
- Without using the Makefile you can do ```docker-compose up```

## Configuration

Under folder litestream/litestream.yml is required to start up and access-key-id, secret-access-key should be set to whatever you have configured in minio.


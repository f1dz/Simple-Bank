GO Bank - Udemy Course
======================

Starting the app
```shell
docker compose up -d
```

Migration
-------------
To start migration you need to install the `golang-migration` first, follow this [LINK](https://github.com/golang-migrate/migrate).
On macOS, you can simply install by run:
```shell
brew install golang-migration
```

Run the migration
```shell
make migrateup
```

Testing
-------
Run the testing
```shell
make test
```
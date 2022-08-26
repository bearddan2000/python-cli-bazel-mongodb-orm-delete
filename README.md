# python-cli-bazel-mongodb-orm-delete

## Description
A mongoengine example w/o login.
Creates a single collection `weapon`
inside `test` database. Inserts multiple
records then prints the whole
collection and the collections inside
`test` database.
Deletes a single record.

## Tech stack
- bazel
- python
  -   mongoengine
- mongodb

## Docker stack
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

# Credits
[Examples](https://www.tutorialspoint.com/mongoengine/index.htm)

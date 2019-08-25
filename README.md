# Jets Project

This README would normally document whatever steps are necessary to get the application up and running.

Things you might want to cover:

* Dependencies
* Configuration
* Database setup
* How to run the test suite
* Deployment instructions

# Local development

### Run DynamoDB Local
```shell script
$ docker pull amazon/dynamodb-local
$ docker run -p 8000:8000 amazon/dynamodb-local
```

If you want to show DynamoDB Local GUI console, do below.

```shell script
$ npm install dynamodb-admin -g
$ DYNAMO_ENDPOINT=http://localhost:8000 dynamodb-admin
```
http://localhost:8001

### Run Jets server
```
$ jets server
```
http://localhost:8888

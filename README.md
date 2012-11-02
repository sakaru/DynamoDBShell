DynamoDBShell
=============

NodeJS shell for Amazon DynamoDB

Usage:
```bash
$ sudo npm install -g DynamoDBShell
# The exports can be put into your ~/.bashrc
$ export DynamoDBaccessKeyId=123456
$ export DynamoDBsecretAccessKey=1234567890
$ dynamodbshell
> scan tables
[ { foo: 'bar', baz: 'foobar' },
  { foo: 123, baz: 456 } ]
Count: 2
> scan foos
[ { foo: 'bar', baz: 'foobar' },
  { foo: 123, baz: 456 } ]
Count: 2
> get bar from foos
{ foo: 'bar', baz: 'foobar' }
> save as bar.js
Saved to bar.js
> quit
Goodbye ☺
```

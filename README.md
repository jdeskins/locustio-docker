
## Usage

Build and run the docker image:

```shell
$ docker build -t mylocustio .
$ docker run --rm -p 8089:8089 mylocustio --host=http://example.com
```

This will run `locustfile.py` in the root of your project.


## Usage

Build and run the docker image:

```shell
$ docker build -t mylocust .
$ docker run --rm -P mylocust
```

This will install any requirements in `requirements.txt` and run `locustfile.py` in the root of your project

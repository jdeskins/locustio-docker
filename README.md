
## Usage

Build and run the docker image:

```shell
$ docker build -t mylocustio .
$ docker run --rm -P mylocustio
```

This will install any requirements in `requirements.txt` and run `locustfile.py` in the root of your project

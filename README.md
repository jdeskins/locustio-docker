
## Usage

Build and run the docker image:

```shell
$ docker build -t jdeskins/locustio .
$ docker run --rm -p 8089:8089 jdeskins/locustio --host=http://example.com
```

This will run `locustfile.py` in the root of your project.

If the locust file is located elsewhere we could run:

```shell
$ docker run --rm -p 8089:8089 jdeskins/locustio -f ../locust_files/my_locust_file.py --host=http://example.com
```

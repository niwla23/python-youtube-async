This library supports Python 3.6 and newer.

## Dependencies

These following distributions will be installed automatically when installing Python-Youtube.

- [requests](https://2.python-requests.org/en/master/): is an elegant and simple HTTP library for Python, built for human beings.
- [Requests-OAuthlib](https://requests-oauthlib.readthedocs.io/en/latest/): uses the Python Requests and OAuthlib libraries to provide an easy-to-use Python interface for building OAuth1 and OAuth2 clients.
- [isodate](https://pypi.org/project/isodate/): implements ISO 8601 date, time and duration parsing.

## Installation

You can install this library from **PyPI**

```shell
$ pip install --upgrade python-youtube
```


Also, you can build this library from source code

```shell
$ git clone https://github.com/niwla23/python-youtube-async.git
$ cd python-youtube
$ make env
$ make build
```

## Testing

If you have been installing the requirements use ``pipenv install --dev``.
You can use following command to test the code

```shell
$ make test
```

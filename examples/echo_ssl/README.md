# echo_server

[![Package Version](https://img.shields.io/hexpm/v/echo_server)](https://hex.pm/packages/echo_server)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/echo_server/)

## Quick start

```sh
gleam run   # Run the project
gleam test  # Run the tests
gleam shell # Run an Erlang shell
```

```sh
# from OpenSSL suite:
$ ./generate-keys.sh
$ gleam run
# > Listening on port: 41145
# copy port number, e.g. 41145
$ openssl s_client -connect localhost:41145
```

## Installation

If available on Hex this package can be added to your Gleam project:

```sh
gleam add echo_server
```

and its documentation can be found at <https://hexdocs.pm/echo_server>.

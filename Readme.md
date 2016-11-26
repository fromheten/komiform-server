# komiform-server

## Installation

* Download Docker
* `docker build -t komiform .`

## Usage

The server is using Docker. Have it installed, and then run `$ make` in the root of this project.

You can now hit the 2 endpoints: `GET http://localhost/form/:form-id` and `POST http://localhost/form` with a form in your body.

## Developing

To develop, you need to have [Leiningen](http://leiningen.org/) and a [JVM](http://openjdk.java.net/).

## License

Copyright © 2016 Martin Josefsson
GNU GPL v3

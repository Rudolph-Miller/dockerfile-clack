# Dockerfile-Clack - Dockerfile for Clack.
[![Build Status](https://circleci.com/gh/Rudolph-Miller/dockerfile-clack.svg?style=shield)](https://circleci.com/gh/Rudolph-Miller/dockerfile-clack)

## Usage

```
FROM rudolphm/clack:latest
MAINTAINER Rudolph Miller


ADD app.lisp /usr/local/src/clack-test/

ENTRYPOINT ["woo", "--port", "80", "/usr/local/src/clack-test/app.lisp"]
EXPOSE 80
```

With this image (rudolphm/clack), you can use some commands and these commands is in /usr/local/bin/.

- ros
  - [Roswell](https://github.com/snmsts/roswell)
- clackup
  - [Clack](https://github.com/fukamachi/clack)
- woo
  - [Woo](https://github.com/fukamachi/woo)
- qlot
  - [qlot](https://github.com/fukamachi/qlot)

## Author

* Rudolph Miller

## Copyright

Copyright (c) 2015 Rudolph Miller

## License

Licensed under the MIT License.

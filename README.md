# restfulpy
A tool-chain for creating restful web applications.

[![Build Status](http://img.shields.io/pypi/v/restfulpy.svg)](https://pypi.python.org/pypi/restfulpy)
[![Gitter](https://img.shields.io/gitter/room/Carrene/restfulpy.svg)](https://gitter.im/Carrene/restfulpy)
     
## Branches

### master

[![Build Status](https://travis-ci.org/Carrene/restfulpy.svg?branch=master)](https://travis-ci.org/Carrene/restfulpy)
[![Coverage Status](https://coveralls.io/repos/github/Carrene/restfulpy/badge.svg?branch=master)](https://coveralls.io/github/Carrene/restfulpy?branch=master)

### develop

[![Build Status](https://travis-ci.org/Carrene/restfulpy.svg?branch=develop)](https://travis-ci.org/Carrene/restfulpy)
[![Coverage Status](https://coveralls.io/repos/github/Carrene/restfulpy/badge.svg?branch=develop)](https://coveralls.io/github/Carrene/restfulpy?branch=develop)



## Goals:
 
- Automatically transform the SqlAlchemy models and queries into JSON with standard 
naming(camelCase).
- Http form validation based on SqlAlchemy models.
- A testing framework for REST application
- Generating the REST API documentation while the tests are passing. It helps to 
always deliver fresh API documentation.


## Contribution

To pass all tests, you have to install postgres > 9.5



#### Enabling the bash auto completion for restfulpy

```bash
$ echo "eval \"\$(register-python-argcomplete restfulpy)\"" >> $VIRTUAL_ENV/bin/postactivate
$ deactivate && workon restfulpy
```

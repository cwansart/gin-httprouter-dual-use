# gin httprouter dual use
This is a test to use the same features with gin and httprouter and compare their output size.

*The httprouter part is not finished yet. Recovery and logger middlewares are missing.*

## Binary sizes
|       | gin                 | httprouter                   |
|-------|---------------------|------------------------------|
|windows|9,60 MB (10.071.040 Bytes)|6,42 MB (6.741.504 Bytes)|

## TODO
### httprouter
* remove httprouter.Params, see: https://github.com/julienschmidt/httprouter#why-doesnt-this-work-with-httphandler
* implement custom logger
* implement recovery middleware
* fix shutdown
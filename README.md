# Build the latest OpenSSL by docker container.

#### OS base on Alpine 64-bit (3.8)

``` alpine:3.8 ```

### I don't know how to get the latest version of OpenSSL, like openssl-latest.tar.gz
### So I have to put the version here
## OPENSSL VERSION=```1.0.2u```

## Build and run

    docker build -t "openssl-test" .
    docker run --rm -it jbouwh/openssl-test [arguments]

or
   
    docker run --rm -it jbouwh/openssl-test [arguments]

# NetCat TCP Half-open Functionality

Moving from CentOS v6 to CentOS v7 presented a problem. Those familiar with
`nc -z` will notice that recent versions of netcat no longer offer that
argument.

This Docker container provides a way to run the old version of netcat.

## Build the Container

```Bash
# In directory with Dockerfile
docker build -t nc-z .
```

## Running

### Option One

```Bash
docker run nc-z host.example.com 8888
```

### Option Two

Set up a Bash function.

```Bash
function nc-z () {
    docker run nc-z ${@}
}
```

Then, just run:

```Bash
nc-z host.example.com 8888
```

# Node.JS Development Environment

A Base setup for Node.JS stack development based on Docker.

## Requirements

[Download Docker](https://www.docker.com/products/docker-desktop) for your operational system.

## Start the development environment

1 - Clone this repository:
```console
$ git clone https://github.com/pdpl89/sturdy-succotash
```

2 - Inside the repository folder, run the shellscript:

```console
$ ./start.sh
```

The environment will provision automatically. After finishing(Around 1 to 3 minutes), check the terminal again and you'll see
the container prompt ready to be used.



**NOTE:** 

* The folder where all source code files must be is the folder **/src** folder  on your host machine.
* Check/Change the ports you need in the Dockerfile and docker-compose.yml files.



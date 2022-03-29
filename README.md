# bpkg-docker

This is a package placeholder for checking or installing Docker into a Linux server using `bpkg`

## Install

```shell
bpkg install javanile/bpkg-docker
```

```version
$ docker --version
Docker version 20.10.7, build 20.10.7-0ubuntu5~20.04.2
```

## Usage

Create a file `bpkg.json` into your shell project with the follow 

```json
{
  .
  .
  "dependencies": {
    "javanile/bpkg-docker": "20.0.0"
  }
  .
  .
}
```

With this you have Docker into your system

# docker-with-java-demos

## docker-multi-stage-build-demo

To build the image: 

```shell
$ cd docker-multi-stage-build-demo
$ docker build -t shyamite/docker-multi-stage-build-demo:1.0-SNAPSHOT .
```

## docker-normal-build-demo

To build the image:

```shell
$ cd docker-normal-build-demo
$ docker build -t shyamite/docker-normal-build-demo:1.0-SNAPSHOT .
```

## docker-package-only-build-demo

First, package the source code:

```shell
$ cd docker-package-only-build-demo
$ mvn clean package
```

Then, build the image:
```shell
$ docker build -t shyamite/docker-normal-build-demo:1.0-SNAPSHOT .
```
These are example projects that correlate  [here](https://adotpalindrome.wordpress.com/2020/02/25/three-ways-to-create-docker-images-for-java/).

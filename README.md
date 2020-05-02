# cobol-hello-world

## On Ubuntu

``` 
$ sudo apt install open-cobol
$ cobc -free -x main.cob
$ ./helloworld
Hello world!
$
```

## Using pack with cobol-buildpack
```
$ pack build cobol-hello-world --path ./ --buildpack dashaun/cobol-buildpack
```

Now you can run that image:

``` 
$ docker run -it cobol-hello-world
Hello world!
$
```
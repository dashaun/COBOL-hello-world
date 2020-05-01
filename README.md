# cobol-hello-world

## On Ubuntu

``` 
$ sudo apt install open-cobol
$ cobc -free -x helloworld.cob
$ ./helloworld
Hello world!
$
```

## On Ubuntu using cobol-buildpack
```
$ pack set-default-builder cloudfoundry/cnb:cflinuxfs3
$ pack build cobol-hello-world --path ./ --buildpack dashaun/cobol-buildpack
```
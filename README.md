### How to Use
#### npm link
```
$ cd package-A
$ npm link
$ cd ../package-B
$ npm link tos-package-sample-A
$ node index
```

#### npm pack
```
$ cd package-A
$ npm pack
$ cd ../package-B
$ npm i ../package-A/tos-package-sample-a-1.0.0.tgz
$ node index
```

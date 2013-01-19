

* Create a temporary directory if testing stuff, else within your own logical
  directory path

```sh
$ cd $(mktemp -d)
```

* Any git project that is new. If it is an existing one not in the git-flow
  strategy, still initiate and push. Optionally you may choose to use prefixes
  or some other naming scheme as is done with features/x or x-something

```sh
$ git-flow init
$ git push -u origin develop
```



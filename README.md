mongokoo
========

Export and import all collections from a mongodb database into/outof a single tarball


### Usage

```shell
$ ./mongokoo -h

usage: ./mongokoo.sh [options] <DBNAME>

OPTIONS:
    -h      Show this help.
    -l      Load instead of export
    -u      Mongo username
    -p      Mongo password
    -H      Mongo host string (ex. localhost:27017)

```

#### example export

```shell
$ ./mongokoo -H localhost:27017  mongodb_db_name

```

#### example export

```shell

$ ./mongokoo ./mongokoo.sh -l gust_tweet -H localhost:27017

```


### TODO
- file output should be using date of import
- add parameter to exclude some collections

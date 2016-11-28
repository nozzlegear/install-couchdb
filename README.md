# install-couchdb

Simple CouchDB 2.0 installation script

Usage:

```
mkdir temp
cd temp
wget https://raw.githubusercontent.com/afiskon/install-couchdb/master/install-couchdb.sh
sh install-couchdb.sh
# then see http://localhost:5984/_utils/
```

Tested on Ubuntu 16.04

## TODO: 

- runit doesn't install properly on fresh Ubuntu images, due to Ubuntu now using systemd. Use [this answer on StackOverflow](http://askubuntu.com/a/665742) to fix the script after it errors out.

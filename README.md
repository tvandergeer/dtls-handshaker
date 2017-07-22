# dtls-handshaker
Client that reproduces Kurento segfault

## introduction ##

See [this post](https://groups.google.com/d/msg/kurento/AJdjdJvFmyg/2Qg7mVYRCAAJ) in the Kurento Google Group.

## dependencies ##
* vagrant
* kurento server running [the hello world example](https://github.com/Kurento/kurento-tutorial-node/tree/master/kurento-hello-world)


## instructions ##
1. clone repo
2. cd vagrant
3. vagrant up
4. vagrant ssh
5. cd /client
6. node index.js wss://localhost:8443/helloworld

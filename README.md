# Local Kafka Infrastructure


something


To run locally using Docker Compose

```
$ docker-compose up
```

By default, the Kafka service will listen on port 9092 on your 129.67.84.1.


It is often useful to set up a hosts entry so that your Kafka instance can be reached by the host reported by zookeeper.

A sample entry for a hosts file is provided in [sample-hosts-file.txt](sample-hosts-file.txt).


A script is included to make it easy for you to set up a couple of Kafka topics. 

All you have to do is run the following command from a Docker-enabled terminal:

```
$ ./setupSampleTopics.sh
```

This script also shows you how you can interact with your docker-hosted Kafka instance.


Originally created by walter on Wed Jun 29 2016 23:01:20 GMT+0000 (UTC).


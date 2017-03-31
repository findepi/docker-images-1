# mapr52-hive-kerberized 

Docker image with kerberos enabled for MapR. Please note that running services have lower memory heap size set.
For more details please check the [hadoop-env.sh](files/conf/hadoop-env.sh) configuration file.
If you want to work on larger datasets please tune those settings accordingly, the current settings should be optimal
for general correctness testing.

## Run

```
$ docker run --privileged -d --name hadoop-master -h hadoop-master teradatalabs/mapr52-hive-kerberized
```

## Oracle license

By using this image, you accept the Oracle Binary Code License Agreement for Java SE available here:
[http://www.oracle.com/technetwork/java/javase/terms/license/index.html](http://www.oracle.com/technetwork/java/javase/terms/license/index.html)
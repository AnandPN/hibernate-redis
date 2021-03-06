# Hibernate-Redis Change logs

### 2.1.1

- change build tool from maven to gradle.

### 2.1.0

- [bugfix] fix dependencies 

### 2.0.4

- [improve] cache set by Redisson `fastPut` instead of `put`
- [update] library update (Redisson 2.3.0)

### 2.0.3

- [bugfix] fix : not found dependency library (hibernate-redis-client...)
           add gradle shadow task

### 2.0.2

- [improve] add more information to README.md
- [new] change build tool from Maven to Gradle (Build QueryDSL annotation process for Gradle)
- [improve] upgrade Redisson 2.2.17

### 2.0.1

- [bigfix] fix loading expiry property value.

### 2.0.0

Sorry for stopping developments (I was leaved from Java a while)

- [new] Support hibernate 4 and hibernate 5 both !!!
- [new] Change redis driver from [Jedis](https://github.com/xetorthio/jedis) to [Redisson](https://github.com/mrniko/redisson)
- [new] Support Redis Cluster, Elasticache, Sentinel, Master-Slaves
- [new] Hibernate Example code update for Hibernate 5 and QueryDSL 4.x
- [todo] Build tool changes from maven to gradle (help me ...)

##### Known Bugs

 - entity with composite id is not serialize/deserialze by [FST](https://github.com/RuedigerMoeller/fast-serialization)

### 1.6.2

1. [improve] support JDK 1.8

### 1.5.8

1. [bug]  change type of regionNames in AbstractRedisRegionFactory for thread-safe.
2. [improve] change korean message to english

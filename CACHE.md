Invidual CACHE for Spring Boot (In Memory)
=======================

spring-boot-starter-cache

Pros
--------
Auto configured
Comes from within framework
All can be controlled using annotations
Multipule cache support (Values stored in multipule cache places can be checked and fetched at a shot)
Simultaneus access possible(Update the data while accessing it -OLD values supplied but will be supplied)
Default : ConcurrentMapCacheManager

Same abstraction can be use with CACHE providers(https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-caching.html)
======================================
JCache (JSR-107) (EhCache 3, Hazelcast, Infinispan, and others)
EhCache 2.x
Hazelcast
Infinispan
Couchbase
Redis
Caffeine
Simple


3 major players comparision:https://db-engines.com/en/system/Hazelcast%3BNCache%3BRedis


Startegies:
========

Read Through / Lazy Loading: Load when needed
When data is needed llok into cache if no found load it use it.

https://medium.com/datadriveninvestor/all-things-caching-use-cases-benefits-strategies-choosing-a-caching-technology-exploring-fa6c1f2e93aa

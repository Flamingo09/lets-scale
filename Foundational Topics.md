Any system has basically these components:
```
1. Database
2. Caching
3. Delegation - Things which are not needed in real time should be done asynchronously
4. Concurrency
5. Scaling
6. Communication
```

#### Database
##### Types of Databases:
   * In-memory
   * Disk Based
   * Server'ed
   * [Embedded](https://medium.com/walmartglobaltech/https-medium-com-kharekartik-rocksdb-and-embedded-databases-1a0f8e6ea74f)
   * Row based
   * Columnar
   * Graph DB
   * Time series DB
   * Relational
   * Non- Relational
   * Blob storage
   * Flat file storages
   * Storages for text-based search
Benefits of using unix epoch : Handles timezone, fast date comparisions. Uses 4 byte
Datetime : More date range. 8 byte

[System Design — Redundancy and Replication](https://medium.com/must-know-computer-science/system-design-redundancy-and-replication-e9946aa335ba)
1. Database Redundancy \
    -> Stand By \
    -> 1:1 \
    -> N:N
    
2. Storage Redundancy \
    -> [RAID](https://searchstorage.techtarget.com/definition/RAID) \
    -> Geo Redundancy \
    -> Datacenter Redundancy

#### Caching
##### Types of caching:
  * Application Server Cache - Request layer cache
  * Central Cache - Redis. Memcached
  * Central and Distributed Cache - Sharded data
  * Content Delivery Network - Akamai, Cloudfare
  * Next to DB - seamless access and transact
  * Disk cache, CPU cache, GPU cache

Cache eviction policies:
  * FIFO
  * LIFO
  * LRU
  * MRU
  * LFU
  * Random Replacement
  
Types of caching Systems:
* Write through Cache
* Write around Cache
* Write-Back Cache

#### Some extra topics:
1. Serverless architecture
2. Elastic Search

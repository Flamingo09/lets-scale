Any system has basically these components:
```
1. Database
2. Caching
3. Delegation - Things which are not needed in real time should be done asynchronously
4. Concurrency
5. Scaling
6. Communication
```

#### Types of Databases:
   * In-memory
   * Disk Based
   * Server'ed
   * Embedded
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

1. Database Redundancy \
    -> Stand By \
    -> 1:1 \
    -> N:N
    
2. Storage Redundancy \
    -> RAID
    -> Geo Redundancy \
    -> Datacenter Redundancy
    
3. Serverless architecture

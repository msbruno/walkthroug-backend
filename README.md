# walkthroug-backend
A Walkthrough to Back-End Development

System Design


Heartbeat mecanism: https://martinfowler.com/articles/patterns-of-distributed-systems/heartbeat.html



Caching:
- What is: 
- Cache Policies: https://en.wikipedia.org/wiki/Cache_replacement_policie
- Problems with poor cache:
  - Poor policy could lead to a scenario where hit the cache has no use.
  - Trashing: when you are constantly inputing and outputing data into the cache   
  - Data consistancy:
    - Write-through: Write it in cache before write in DB. 
    - Write-back: delete the entry for X and update the database. When there is a query for X, get it and writ it in cache.   


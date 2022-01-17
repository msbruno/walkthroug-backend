# walkthroug-backend
A Walkthrough to Back-End Development

System Design

## Database:


## Caching:
- What is: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Caching
- Cache Policies: https://en.wikipedia.org/wiki/Cache_replacement_policie
- Problems with:
  - Poor cache policy could lead to a scenario where hit the cache has no use.
  - Trashing: when you are constantly inputing and outputing data into the cache   
  - Data consistancy: 
    - Write-through: Write it in cache before write in DB. 
    - Write-back: delete the entry for X and update the database. When there is a query for X, get it and writ it in cache. 
    
      
Heartbeat mecanism: https://martinfowler.com/articles/patterns-of-distributed-systems/heartbeat.html


## Blockchain 

Cryptography and Consensus: https://www.youtube.com/watch?v=V0JdeRzVndI&ab_channel=TechCrunch

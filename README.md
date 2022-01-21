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

# Miscellaneous
- Fallacies of Distributed Computing: Explainedhttps://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf

# Blogs to follow
- http://highscalability.com/

## Blockchain and Crypto
- How it works(simple): https://www.youtube.com/watch?v=SSo_EIwHSd4&t=101s
- How it works: https://www.youtube.com/watch?v=2wxtiNgXBaU
- Visual how it works: https://www.youtube.com/watch?v=_160oMzblY8
- How proof of stake works: https://www.youtube.com/watch?v=M3EFi_POhps
- Smart Contracts: https://www.youtube.com/watch?v=ZE2HxTmxfrI
- Halving: https://www.youtube.com/watch?v=dtYJrZNct-o
- Hash rate: https://www.youtube.com/watch?v=dtYJrZNct-o
- Consensus: https://www.youtube.com/watch?v=BbCy2mu7XiA
- Cryptography and Consensus: https://www.youtube.com/watch?v=V0JdeRzVndI
- The future of NFT: https://www.youtube.com/watch?v=sKxxc_cfwR0&t=353s

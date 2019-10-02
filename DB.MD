## Join

+ `A Left Join B on A.id = B.a_id` vs `A Left Join B where A.id = B.a_id` 
  - if B has nothing to join A, then `on` will keep some A whereas `where` will return nothing at all.

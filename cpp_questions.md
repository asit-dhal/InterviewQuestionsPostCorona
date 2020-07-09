1. Difference between std::map and std::unordered_map. In what use case, std::unorderd_map is better than std::map ? 
  - iterator invalidation
  - taking advantage of cache memory in modern processor
  - std::map 's feature of sorted keys
  - std::map 's key requirement of "strict weak order",  and std::unorderd_map's requirement of hash function and comparision function of equality

2. std::vector related questions
  - iterator invalidation
  - difference between push_back(const &), push_back(T&&) and emplace_back(Args && ...)
  - questions where resize invalidates iterator and emplace_back on std::vector<std::vector<int> >
  
3. std::move and std::forward, questions related to perfect forwarding

4. In what case, virtual destructor in polymorphic base class is not required ?

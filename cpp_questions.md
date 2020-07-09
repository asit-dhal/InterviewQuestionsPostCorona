### Difference between std::map and std::unordered_map. 
  - In what use case, std::unorderd_map is better than std::map ? 
  - iterator invalidation
  - taking advantage of cache memory in modern processor
  - std::map 's feature of sorted keys
  - std::map 's key requirement of "strict weak order",  and std::unorderd_map's requirement of hash function and comparision function of equality

### std::vector related questions
  - iterator invalidation(questions where resize invalidates iterator)
  - difference between push_back(const &), push_back(T&&) and emplace_back(Args && ...)
  - emplace_back on std::vector<std::vector<int> >
  
### move semantics
  - a class has only primitive types, why compiler provided move member functions are just enough ?
  - a class has user provided copy member functions, but deleted move member functions, but std::move() works ?
  - why string literals are l-value refernces, but integer literals are r-value references ?
  - tricky examples where move semantics are not passed through

### Classical C++
  - In what case, virtual destructor in polymorphic base class is not required ?

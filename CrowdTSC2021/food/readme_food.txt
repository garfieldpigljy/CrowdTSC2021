1. food_tsclabels.csv
triplet similarity comparison labels. 

- A : image ID, anchor object
- B : image ID
- C : image ID
- eval: 1(A is more similar to B than to C) or 0(A is more similar to C than to B)
- worker: worker ID


2. food_tscgt_by_category.csv
triplet ground truth based on image true category. A and B are from same category, C is from another category. 

- A : image ID, anchor object
- B : image ID
- C : image ID
- eval: 1(A is more similar to B than to C) or 0(A is more similar to C than to B)


3. food_category_list.csv
object category list. 

- index : image ID
- category: image true category
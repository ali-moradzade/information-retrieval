# Information Retrieval System  

## Phase1 - Positional index

The most important steps done in this phase:
-  Preprocessing:   
    - Deleting some extra stuff in content 
    - Deleting punctuation
    - Doing normalization
    - Doing tokenization
    - Doing stemming
    - Removing stop words
 - Building the positional postings list
 - Searching inside our index:
   - Processing queries
   - Searching one word with positional index
   - Find the documents, that contain all the words in the list
   - Implementing multi word search:
   - Complete Search (also considering Not !)
 - Plotting zipf and heaps
<br><br>
## Phase2 - Efficient query responding by heap and champion list
In this phase, we improve IR system accuracy and speed with famous IR techniques.  
The most important steps implemented in this phase:
- tf-idf Vector representation for docs
- Similarity calculation (cosine-sim)
- Index elimination
- Champion list (tf base)
- K-top extraction by max-heap
- Pharase query responding (Ranked Retrieval system) 
<br><br>
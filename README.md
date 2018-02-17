# AlgorithmEngineering

implementation of some algorithms seen during the Algorithm Engineer course @ UniPi.

[Official notes](http://didawiki.di.unipi.it/lib/exe/fetch.php/magistraleinformaticanetworking/ae/ae2017/main_2.pdf) of the course.

Chapters:

3 Random Sampling
------------------

- Drawing from all un-sampled positions
- Dictionary of sampled positions
- Sorting sampling
- Scanning an selecting
- Heap and random keys
- Reservoir sampling

4 List Ranking
------------------
 
- Pointer jumping technique
- Divide&Conquer approach

5 Sorting Atomic Items
------------------
 
- Binary Merge sort
- Snow Plow
- Three-way Quick sort
- Rand select
- Bounded space Quick sort
- Dual Pivot Quick sort

6 Set Intersection
------------------
 
- Merge-based Set intersection ([merge_intersection.hpp](Chap.06/merge_intersection.hpp))
- Binary-search-based Set intersection ([binary_search.hpp](Chap.06/binary_search_intersection.hpp))
- Mutual Partitioning Set intersection ([mutual_partitioning.hpp](Chap.06/mutual_partitioning.hpp))
- Doubling Search Set intersection ([doubling_search.hpp](Chap.06/doubling_search.hpp))

7 Sorting Strings
------------------
 
- MSD Radix sort
- LSD Radix sort
- Multikey Quick sort

8 The Dictionary Problem
------------------
 
- Order Preserving Minimal Perfect Hash Function
- Two-Level hashing 
- Cuckoo hashing
- Bloom Filters

9 Searching Strings by Prefix
------------------
 
- Compacted Trie
- Patricia Trie 

10 Searching Strings by Substring
------------------
 
- Suffix Array 
- LCP Array 
- Suffix Tree
- Approximate-pattern matching
- LCA via RMQ

11 Integer Coding
------------------
 
- Binary code ([binary_code.hpp](Chap.11/binary_code.hpp))
- Unary code ([unary_code.hpp](Chap.11/unary_code.hpp))
- Fixed-Length code ([fixed_length_code.hpp](Chap.11/fixed_length_code.hpp))
- Elias Gamma code ([elias_gamma_code.hpp](Chap.11/elias_gamma_code.hpp))
- Elias Delta code ([elias_delta_code.hpp](Chap.11/elias_delta_code.hpp))
- Rice code ([rice_code.hpp](Chap.11/rice_code.hpp))
- PForDelta code ([pfordelta_code.hpp](Chap.11/pfordelta_code.hpp))
- Variable-byte code ([variable_byte_code.hpp](Chap.11/variable_byte_code.hpp))
- (s,c)-dense code ([sc_dende_code.hpp](Chap.11/sc_dende_code.hpp))
- Interpolative code ([interpolative_code.hpp](Chap.11/interpolative_code.hpp))
- Elias-Fano code ([elias_fano.hpp](Chap.11/elias_fano.hpp))

12 Statistical Coding
------------------
 
- Huffman coding
- Canonical Huffman
- Arithmetic Coding

13 Dictionary-based compressors
------------------
 
- LZ77
- LZSS
- LZ78
- LZW

14 The Burrows-Wheeler Transform
------------------
 
- Burrows-Wheeler Transform
- Move-To-Front Transform
- Run-Length-Encoding Transform
- BZip compressor

0 Extra
------------------
 
- Minimum Spanning Tree: Kruskal
- Minimum Spanning Tree: Prim
- Minimum Spanning Tree: Sibeyn
- Skip List
- Treap


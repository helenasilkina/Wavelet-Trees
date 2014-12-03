The wavelet tree, invented by Grossi, Gupta, and Vitter[1] as a data structure to represent a sequence and answer some queries on it, is an important data structure with a vast number of applications to stringology, computational geometry, and others[2].

There are optimised search methods using the suffix array combined with auxiliary data structures, such as the LCP (longest-common prefix) array, or wavelet trees. See for details [3].

A Wavelet Tree converts a string into a balanced binary-tree of bit vectors, where a 0 replaces half of the symbols, and a 1 replaces the other half. This creates ambiguity, but at each level this alphabet is filtered and re-encoded, so the ambiguity lessens, until there is no ambiguity at all. Given a 25-letter English alphabet indexed from 0 to 25 the string 'bananaaa' becomes 1,1,13,1,1,1,0,0.

For a string w of length n, this data structure occupies O(n) words, takes O(n√log n) time to construct, and simultaneously captures the combinatorial structure of substrings of w while enabling efficient top-down traversal and binary search.

1. <a href="http://www.di.unipi.it/~grossi/PAPERS/soda04.pdf">Luca Foschini, Roberto Grossi, Ankur Gupta, and Jeffrey Scott Vitter. When indexing equals compression: experiments with compressing suffix arrays and applications. ACM Transactions
on Algorithms, 2(4):611–639, October 2006.</a>
2. <a href="http://www.dcc.uchile.cl/~gnavarro/ps/cpm12.pdf">Gonzalo Navarro. Wavelet trees for all. Journal of Discrete Algorithms: 23rd Annual Symposium on Combinatorial Pattern Matching, 25:2–20, 2014</a>
3. <a href="http://www.captura.uchile.cl/bitstream/handle/2250/6348/Navarro_Gonzalo-%20suc.pdf?sequence=1">G. NAVARRO, V. MAKINEN Compressed Full-Text Indexes</a>
4. <a href="http://arxiv.org/pdf/1408.6182v3.pdf">Maxim Babenko, Pawe l Gawrychowski, Tomasz Kociumaka, and Tatiana Starikovskaya1 Wavelet Trees Meet Suffix Trees</a>

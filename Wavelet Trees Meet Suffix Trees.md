<a href="http://arxiv.org/pdf/1408.6182v3.pdf">Wavelet Trees Meet Suffix Trees</a>

Maxim Babenko, Pawe l Gawrychowski, Tomasz Kociumaka, and Tatiana Starikovskaya

We present an improved wavelet tree construction algorithm and discuss its applications to a number of rank/select problems for integer keys and strings.

Given a string of length n over an alphabet of size σ ≤ n, our method builds the wavelet tree in O(n log σ/√log n) time, improving upon the state-of-the-art algorithm by a factor of √log n. As a consequence, given an array of n integers we can construct in O(n√log n) time a data structure consisting of O(n) machine words and capable of answering rank/select queries for the subranges of the array in O(log n/ log log n) time. This is a log log n-factor improvement in query time compared to Chan and P˘atra¸scu (SODA 2010) and a √log n-factor improvement in construction time compared to Brodal et al. (Theor. Comput. Sci. 2011).

Next, we switch to stringological context and propose a novel notion of wavelet suffix trees. For a string w of length n, this data structure occupies O(n) words, takes O(n√log n) time to construct, and simultaneously captures the combinatorial structure of substrings of w while enabling efficient top-down traversal and binary search. In particular, with a wavelet suffix tree we are able to answer in O(log |x|) time the following two natural analogues of rank/select queries for suffixes of substrings:

<a href="http://arxiv.org/pdf/1408.6182v3.pdf">Wavelet Trees Meet Suffix Trees</a>

Maxim Babenko, Pawe l Gawrychowski, Tomasz Kociumaka, and Tatiana Starikovskaya

We present an improved wavelet tree construction algorithm and discuss its applications to a number of rank/select problems for integer keys and strings.

Given a string of length n over an alphabet of size σ ≤ n, our method builds the wavelet tree in O(n log σ/√log n) time, improving upon the state-of-the-art algorithm by a factor of √log n. As a consequence, given an array of n integers we can construct in O(n√log n) time a data structure consisting of O(n) machine words and capable of answering rank/select queries for the subranges of the array in O(log n/ log log n) time. This is a log log n-factor improvement in query time compared to Chan and P˘atra¸scu (SODA 2010) and a √log n-factor improvement in construction time compared to Brodal et al. (Theor. Comput. Sci. 2011).

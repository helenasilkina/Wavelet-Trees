Вейвлет-деревья, изобретенный Grossi, Гупта, и Vitter[1] в качестве структуры данных для представления последовательности и получения ответа на запросы, применяются в различных приложениях в стрингологии, вычислительной геометрии и других[2].

Вейвлет-дерево преобразует строку в сбалансированное двоичное дерево битовых векторов, где 0 заменяет половину символов, и 1 заменяет другую половину. Это создает двусмысленность, но на каждом уровне этот алфавит фильтруется и повторно перекодируется, так что неопределенность уменьшается до того момоента, когда исчезает двусмысленность. Учитывая, что в английском алфавите 25 букв, индексированных от 0 до 25, то например строка 'bananaaa' превращается в 1,1,13,1,1,1,0,0.

Для слова w длины n, эта структура данных занимает O(n) слов, расходует O(n√log n) времени, чтобы построить, и одновременно составить комбинаторную структуру подстроки w, обеспечивая эффективный нисходящий обход и бинарный поиск.

Есть оптимизированные методы поиска с помощью суффиксного массива в сочетании со вспомогательными структурами данных, такими как LCP (длинный-общий префикс) массив, или вейвлет-деревья. См. подробности в [3].

1. <a href="http://www.di.unipi.it/~grossi/PAPERS/soda04.pdf">Luca Foschini, Roberto Grossi, Ankur Gupta, and Jeffrey Scott Vitter. When indexing equals compression: experiments with compressing suffix arrays and applications. ACM Transactions
on Algorithms, 2(4):611–639, October 2006.</a>
2. <a href="http://www.dcc.uchile.cl/~gnavarro/ps/cpm12.pdf">Gonzalo Navarro. Wavelet trees for all. Journal of Discrete Algorithms: 23rd Annual Symposium on Combinatorial Pattern Matching, 25:2–20, 2014</a>
3. <a href="http://www.captura.uchile.cl/bitstream/handle/2250/6348/Navarro_Gonzalo-%20suc.pdf?sequence=1">G. NAVARRO, V. MAKINEN Compressed Full-Text Indexes</a>
4. <a href="http://arxiv.org/pdf/1408.6182v3.pdf">Maxim Babenko, Pawe l Gawrychowski, Tomasz Kociumaka, and Tatiana Starikovskaya1 Wavelet Trees Meet Suffix Trees</a>

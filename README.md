This repository demonstrates an uncommon Perl bug related to the unordered nature of hash iteration. The bug.pl file contains code that iterates over a hash, expecting a specific order, which is not guaranteed in Perl. The bugSolution.pl file provides a solution using a sorted key list to ensure predictable order.
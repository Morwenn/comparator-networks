## Sorting network, size 29

### Size-optimal network

The size-optimal network of size 29 uses a usual divide-sort-merge strategy as described by David C. Van Voorhis in [*A
Generalization of the Divide-Sort-Merge Strategy for Sorting Networks*][1]: it first sorts the first 16 elements with a
size-optimal 16-sorter, then it sorts the last 12 elements with a size-optimal 12-sorter before merging both collections
with the merge step of a size-32 merge-exchange network whose comparators handling elements after the 29th one have been
removed.

![Size-optimal 29-sorter](https://cdn.rawgit.com/Morwenn/comparator-networks/master/networks/sort/29/size-optimal-29.svg)


  [1]: http://www.dtic.mil/dtic/tr/fulltext/u2/737270.pdf

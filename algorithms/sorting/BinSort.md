# Bin Sort

**MSD**
* Doesn't need to be stable
* Subsequent steps sort each subgroup

**LSD**
* Needs a stable sorting algorithm
* Benefit: each step can sort the whole array at once

**Radix sort**

Decompose the the sort key using some radix *r*. When *r* = 10 we get decimal decomposition, when *r* = 2 we get
binary decomposition of the keys.

The number of bins in radix sort is *r*.

Assume there are *n* records to be sorted and the keys are decomposed using a radix of *r*. This results in each
key having *d* digits in the range 0 to (r-1). Thus we need *r* bins.

**Analysis**
Radix sort makes *d* passes over the input, each pass taking O(n+r) time. Thus the total computing time is
O(d(n+r)). The value of *d* depends on the choice of the radix *r* and on the largest key.



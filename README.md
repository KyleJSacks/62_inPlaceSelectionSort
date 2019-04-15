# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will triple, because the cost of this algorithm is linear to the amount of elements to be cycled through.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by 6 times, because the champIndex algorithm is invoked twice, and if each increases by 3 times, the total cost of both will be 3 times
the cost of one + three times the cost of the other..
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 6 times, because this list cyles through itself via reigning champ, and it does so twice as mentioned above, and so the cost
will grow similarly.
[Justify, in about 2 sentences.]

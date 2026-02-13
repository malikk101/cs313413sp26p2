Malik Khan


Test Results:

Size = 10:
- testArrayListAccess: 0.008s
- testArrayListAddRemove: 0.018s
- testLinkedListAccess: 0.007s
- testLinkedListAddRemove: 0.017s

size = 100:
- testArrayListAccess: 0.009s
- testArrayListAddRemove: 0.026s
- testLinkedListAccess: 0.020s
- testLinkedListAddRemove: 0.021s

size = 1000:
- testArrayListAccess: 0.011s
- testArrayListAddRemove: 0.151s
- testLinkedListAccess: 0.379s
- testLinkedListAddRemove: 0.017s

size = 10000:
- testArrayListAccess: 0.010s
- testArrayListAddRemove: 1.512s
- testLinkedListAccess: 5.146s
- testLinkedListAddRemove: 0.019s

Analysis:

ArrayList is fater for access but slower for add and remove,
while Linked list is the opposite.


Questions:

Q1: Try LinkedList in TestIterator - does it make a difference?
A: No

Q2: What if you use list.remove(Integer.valueOf(77)) in iterator?
A: Throws ConcurrentModificationException

Q3: Try LinkedList in TestList - does it make a difference?
A: No, both implement List interface the same way

Q4: What does list.remove(5) do?
A: Removes at index 5

Q5: What does list.remove(Integer.valueOf(5)) do?
A: Removes first occurrence of 5

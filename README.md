# DAA_ALL_PROGRAM
SOME PROGRAM ALGORITHM LIKE MERGE,QUICK,DIJKSTRA'S,BELLMAN etc
Merge sort:
step 1:divide list into two sublist,almost in equal size.
step 2:sorted left sublist recursively by using merge sort.
step 3:sorted right sublist recursively by using merge sort.
step 4:merge the sorted sublist.
Quick sort:
step 1:Take the first element as a pivot in the list.
step 2:by partition pivot comes in at proper place.all element
      of the pivot left side are less than the pivot and right 
      side all element are greater than the pivot,pivot is an 
      an proper place ,so index will be pivotloc.
step 3:create left sublist of arr[low]---arr[pivot-1] and for
       right sublist arr[pivot+1]----arr[up].
step 4:sorted the left sublist recursively using quick sort.
step 5:sorted the right sublist recursively using quick sort.
step 6:terminating condition for quick sort is take only one
       element and there is not element present in list.
Dijkstra's alogrithm:
step 1:initialized the pathlength of all vertices to infinity
       and predecessor to NIL (-1).make the status the the 
       of all vertices temporary.
step 2:make the pathlength as source is zero.
step 3:from all the temporary vertices find out vertex which 
       has minimum shortest pathlength make it permanent,make
       it current.
step 4:examine all temporary vertices adjacent to current value
       of pathlength is recalculated is requried,relabeling is
       done.
      if PL(current)+wt(current,v)<pl(v)
         pL(v)=PL(current)+wt(current,v)
         predecessor(v)=current
step 5:repeat the step 3 & 4 unitil there is no temporary vertex 
       left in the graph.
Bellman alorithm:
step 1: initialized the pathlength to infinity predecessor to NIL
        (-1).
step 2: the pathlength as source vertex is zero and insert in queue.
step 3:delete the vertex from the front make it current.
step 4:examine all temporary vertices adjacent to current value
       of pathlength if requried relabeling is done.
step 5:each vertex that is relabel is inserted to the queue.
       provided it is not alredy present in queue.
step 6:repeat the step 3,4,5 till the queue becomes empty.

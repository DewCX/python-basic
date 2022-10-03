# Python Basic

Hello everyone , I have completed project called "Python basic" which organized by Patika.dev


### Question 1

`input :[[1,'a',['cat'],2],[[[3]],'dog'],4,5]  `

### Write a function that flattens a list.

### Answer:

    l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
    lnew = [ ]
    def flatten(n):
        for i in n:
            if isinstance(i, list):
                flatten(i)
            else:
                lnew.append(i)
    
    flatten(l)
    print(lnew)



### Question 2

`input: [[1, 2], [3, 4], [5, 6, 7]]`

### Write a function that reverses the elements inside the given list.If the elements inside the list also contain the list, reverse their elements as well.

### Answer:

    l =[ [1, 2], [3, 4], [5, 6, 7] ]
    l= l [ : : -1]
    
    for i in range(len( l )) :
        ( l [ i ] )=( l [ i ] ) [::-1]
    print( l )

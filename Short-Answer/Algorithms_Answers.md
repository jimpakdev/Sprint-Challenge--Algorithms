#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime complexity is O(n).  a = n^3/n^2 = n.  It will take n iterations for a to reach n^3, thus the runtime is linear.  


b) The runtime complexity is O(n^2).  There is a nested 'while loop' within the 'for loop' ( which is O(n) ), thus 
O(n) * O(n) = O(n^2) 


c) Runtime complexity is O(n) because the number of times this function will run is the number of bunnies.  

## Exercise II
n = building_stories    #### initialize values
egg = not_broken
drops = 0

def find_floor_f(n):
    while egg != broken:
        for floor in range( 0 , len(n) + 1 ):    #### O(n)                
            drop egg
                if egg = broken:
                    return floor
                else:
                    drops += 1
        
The runtime complexity of this solution is O(n).  This strategy begins from the ground floor, and drops an egg.  If the egg is not broken, move up to the next consecutive floor and repeat the test.  When the egg is broken when dropped, the floor number will be returned.  The other way I would approach this is with a binary search, but I considered the probability of the initial egg breaking point being located above the midpoint of a given n and went with the linear solution.









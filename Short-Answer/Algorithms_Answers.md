#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
    O(n)
    This is because a = n * n
    While a < n * n * n
    so  a = n 
b)
    This is n^2
    The while loop is O(n)
    The foor loop is O(n)
    so O(n) * O(n) = O(n^2)
c)  
    This is O(n)
    Since this recursion is going over bunnies and substract 1 from it everytime until it becomes 0
    

## Exercise II
    # Understanding the problem
    1. Have many eggs.
    2. On floor higher than floor f.
    3. Drop eggs, eggs broken.
    4. if floor random lower than floor f.
    5. Drop eggs, eggs fine.
    
    So theoratically, the highest floor should have no problem throwing eggs outta window.

    So this is O(n)

    No matter how many eggs, we just need to return the highest floor.

    def find_highest_floor(eggs, n-th_stories_building):
        return max of n_th_stories_building (depending on how this value is passed down to the function)

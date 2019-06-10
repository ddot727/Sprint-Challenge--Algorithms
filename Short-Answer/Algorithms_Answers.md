#Add your answers to the Algorithms exercises here.

`a)` _O(n)_ - The amount of times the while loop would dependent on n (which is linear) and O(n) is the dominate term.

`b)` _O(n^4)_ - The algorithm has 3 nested for loops inside of a for loop. Each for loop has a time complexity of O(n) and since each of them are dependent on the one that comes before, the time the algorithm runs is n * n * n * n.

`c)` _O(n)_ - The amount of times the algorithm needs to run is dependent on the amount of recursive calls which is n.

#Chicken Egg Heist:

def highestFloorStillIntact(n):
    floor = 0 #FirstFloor                    # O(1)
    for floor in range(1, n):                # O(n)
        throwThat egg from floor             # O(1)
        if egg breaks:
            return floor - 1                 # O(1)

Time complexity would be _O(n)_
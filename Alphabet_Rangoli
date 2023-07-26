import string
from math import ceil
from itertools import chain

def print_rangoli(size
    # Your Code Goes Here
    alphabet = string.ascii_lowercase[:size][::-1]
    #alphabet = alphabet[::-1]
    length = 1 + 4 * (size - 1)
    
    chained = chain(range(size), range(size-2, -1, -1))
    
    for i in chained:
        original = "-".join(alphabet[:i+1]).rjust(ceil(length/2), "-")
        mirrored = original[::-1][1:]
        print(original+mirrored)
        
    
    
if __name__ == '__main__':
    n = int(input())
    print_rangoli(n)

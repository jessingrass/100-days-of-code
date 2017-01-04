# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress**: Learned about splicing and working with arrays; still not sure how to get an item from an array and just save the numeric value. Something for tomorrow.

**Thoughts:** I'm slow at coding. Always have been, always will be. But I like learning about all the ways that lists can be manipulated. I'm not sure exactly how this would be used in reality, but I expect that I'll learn more. 

**Link to work:** https://py.checkio.org/mission/even-last/solve/  (links to problem but not to my code, so I posted my work and the tests below)

def checkio(array):
    # start at beginning of list and take every 2nd item
    # then multiply by the last item
    even = array[::2]
        # how do I get the value of the even items, rather than having them return in a list
    final = array[-1]

    #test
    print(even)
    print(final)

#These "asserts" using only for self-checking and not necessary for auto-testing
if __name__ == '__main__':
    assert checkio([0, 1, 2, 3, 4, 5]) == 30, "(0+2+4)*5=30"


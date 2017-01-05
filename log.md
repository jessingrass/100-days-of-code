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

### Day 1: January 4, 2017

**Today's Progress**: I figured out how to get the numbers that I want to return separately. Now I need to figure out how I might assign them to their own variables since right now they just return and I can't figure out how to "do" anything with them. 

**Link to work** and problem same as yesterday. Here's the new code:

def checkio(array):
    for num in array[::2]:
        return num


**Thoughts**: I'm still slow, but forcing myself to do this bit by bit is getting me into parts of Python that I have been able to ignore for a long time because I didn't need them for work, even though it's part of the power of this language. I'm frustrated but in a good way.

# freqofletters
#A program to print the frequency of the letters in a string
str1= input("Please enter a string:")
def most_frequent(str1):               #function
    freq = {}
    for n in str1:
        keys = freq.keys()
        if n in keys:
            freq[n] += 1
        else:
            freq[n] = 1
    return freq
print(most_frequent(str1))

#OUTPUT

Please enter a string:mississippi
{'m': 1, 'i': 4, 's': 4, 'p': 2}

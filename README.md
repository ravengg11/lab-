1)
def pair_sum(a, b):
    return a + b
 
print(pair_sum(int(input()), int(input())))

2)
a = 1,2,3,4 
def max_min(a): 
     return min(a)+max(a) 
max_min(a)

3)
ef count_vowels(text):
    from symbols import is_vowel
    return sum(is_vowel(x) for x in text)

4)
def check_anagram(data1, data2):
    data1 = data1.lower()
    data2 = data2.lower()
    if sorted(data1) != sorted(data2):
        return False
    return all(data1[i] != data2[i] for i in range(len(data1)))

5)
def is_in(x,y):
    if x in y or y in x:
        return True
    else:
        return False
print(is_in("hello","hello world"))  

7) 
ef func(numbers):
    for i in range(1, len(numbers)):
        if numbers[i] < numbers[i - 1]:
            return(False)
    return(True)
    
8) 
a = 2
b = 2
c = 1
def equal(a, b, c):
      if a == b or a == c or b == a or b == c or c == b or c == a:
         return True
      else:
         return false
         
priont(equal(a, b, c))
   

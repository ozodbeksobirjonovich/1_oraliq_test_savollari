1. Quyidagi kodni bajarish natijasi nima bo'ladi?
   ```python
   x = 5
   y = 2
   print(x ** y)
   ```
   
   a) 7  
   b) 25  
   c) 10

2. List elementlarini teskari tartibda chiqarish uchun qaysi usul to'g'ri?
   ```python
   numbers = [1, 2, 3, 4, 5]
   ```
   
   a) print(numbers.reverse())  
   b) print(numbers[::-1])  
   c) print(sort(numbers, reverse=True))

3. Quyidagi funksiyani chaqirish natijasi nima bo'ladi?
   ```python
   def multiply(*args):
       result = 1
       for n in args:
           result *= n
       return result
   print(multiply(2,3,4))
   ```
   
   a) 24  
   b) 9  
   c) 14

4. Dictionary comprehension orqali kvadratlarni hisoblash:
   ```python
   numbers = range(5)
   squares = {x: x**2 for x in numbers}
   print(squares[3])
   ```
   
   a) 6  
   b) 9  
   c) 27

5. While tsikli qachon to'xtaydi?
   ```python
   x = 0
   while x < 5:
       print(x)
       x += 1
   ```
   
   a) x = 4 da  
   b) x = 5 da  
   c) x = 6 da

6. Lambda funksiyasi natijasi nima?
   ```python
   multiply = lambda x,y: x*y
   print(multiply(3,4))
   ```
   
   a) 7  
   b) 12  
   c) 34

7. Set operatsiyasi natijasi nima bo'ladi?
   ```python
   set1 = {1,2,3}
   set2 = {3,4,5}
   print(set1.intersection(set2))
   ```
   
   a) {3}  
   b) {1,2,4,5}  
   c) {1,2,3,4,5}

8. List slicing natijasi:
   ```python
   numbers = [0,1,2,3,4,5]
   print(numbers[2:5])
   ```
   
   a) [2,3,4]  
   b) [2,3,4,5]  
   c) [1,2,3,4]

9. Quyidagi kod nima qaytaradi?
   ```python
   text = "Python"
   print(text[::-1])
   ```
   
   a) nohtyP  
   b) Python  
   c) PYTHON

10. Dictionary metodidan foydalanish:
    ```python
    dict1 = {'a':1, 'b':2}
    print(dict1.get('c', 3))
    ```
    
    a) KeyError  
    b) None  
    c) 3

11. For tsikli necha marta aylanadi?
    ```python
    for i in range(2,8,2):
        print(i)
    ```
    
    a) 3 marta  
    b) 4 marta  
    c) 2 marta

12. List comprehension natijasi:
    ```python
    numbers = [1,2,3,4,5]
    evens = [x for x in numbers if x%2==0]
    print(evens)
    ```
    
    a) [2,4]  
    b) [1,3,5]  
    c) [1,2,3,4,5]

13. Try-except blokida qanday natija chiqadi?
    ```python
    try:
        print(10/0)
    except ZeroDivisionError:
        print("xato")
    ```
    
    a) xato  
    b) 0  
    c) Error

14. Tuple qiymati o'zgaradimi?
    ```python
    t = (1,2,3)
    t[0] = 5
    print(t)
    ```
    
    a) TypeError  
    b) (5,2,3)  
    c) (1,2,3)

15. Set metodining natijasi nima?
    ```python
    s1 = {1,2,3}
    s2 = {3,4,5} 
    print(s1.union(s2))
    ```
    
    a) {1,2,3,4,5}  
    b) {3}  
    c) {1,2,4,5}

16. Map funksiyasi natijasi:
    ```python
    numbers = [1,2,3,4]
    squared = list(map(lambda x: x**2, numbers))
    print(squared)
    ```
    
    a) [1,4,9,16]  
    b) [2,4,6,8]  
    c) [1,2,3,4]

17. Funksiya parametri qanday ishlaydi?
    ```python
    def greet(name="User"):
        print(f"Hello {name}")
    greet()
    ```
    
    a) Hello User  
    b) Hello  
    c) Error

18. List metodining natijasi:
    ```python
    lst = [1,2,3]
    lst.append([4,5])
    print(lst)
    ```
    
    a) [1,2,3,[4,5]]  
    b) [1,2,3,4,5]  
    c) [1,2,3,4]

19. String metodining natijasi:
    ```python
    text = "python"
    print(text.upper())
    ```
    
    a) PYTHON  
    b) Python  
    c) python

20. Dictionary comprehension natijasi:
    ```python
    d = {x:x*2 for x in range(3)}
    print(d)
    ```
    
    a) {0:0, 1:2, 2:4}  
    b) {0:1, 1:2, 2:3}  
    c) {1:2, 2:4, 3:6}

21. While tsikli necha marta aylanadi?
    ```python
    i = 5
    while i > 0:
        print(i)
        i -= 2
    ```
    
    a) 3 marta  
    b) 2 marta  
    c) 5 marta

22. Set operatsiyasi natijasi:
    ```python
    s1 = {1,2,3}
    s2 = {3,4,5}
    print(s1.difference(s2))
    ```
    
    a) {1,2}  
    b) {4,5}  
    c) {1,2,4,5}

23. List slicing natijasi:
    ```python
    numbers = [0,1,2,3,4,5]
    print(numbers[::2])
    ```
    
    a) [0,2,4]  
    b) [1,3,5]  
    c) [0,1,2]

24. Filter funksiyasi natijasi:
    ```python
    numbers = [1,2,3,4,5,6]
    evens = list(filter(lambda x: x%2==0, numbers))
    print(evens)
    ```
    
    a) [2,4,6]  
    b) [1,3,5]  
    c) [1,2,3,4,5,6]

25. String formatlash natijasi:
    ```python
    name = "John"
    age = 25
    print(f"{name} is {age}")
    ```
    
    a) John is 25  
    b) name is age  
    c) John is {age}

26. Lambda funksiyasi natijasi:
    ```python
    func = lambda x: "juft" if x%2==0 else "toq"
    print(func(4))
    ```
    
    a) juft  
    b) toq  
    c) None

27. Tuple bo'shatish natijasi:
    ```python
    t = (1,2,3)
    a,b,c = t
    print(b)
    ```
    
    a) 2  
    b) 1  
    c) 3

28. List metodining natijasi:
    ```python
    lst = [1,2,3,4]
    lst.insert(1,5)
    print(lst)
    ```
    
    a) [1,5,2,3,4]  
    b) [1,2,5,3,4]  
    c) [5,1,2,3,4]

29. Quyidagi kod natijasi nima bo'ladi?
    ```python
    x = ["salom", "dunyo", "python"]
    print(" ".join(x))
    ```
    
    a) salom dunyo python  
    b) ['salom', 'dunyo', 'python']  
    c) salomdunyopython

30. Dictionary metodining natijasi:
    ```python
    d = {'a':1, 'b':2}
    d.update({'c':3})
    print(d)
    ```
    
    a) {'a':1, 'b':2, 'c':3}  
    b) {'a':1, 'b':2}  
    c) Error

31. List comprehension bilan filter:
    ```python
    nums = [1,2,3,4,5,6,7,8,9,10]
    result = [x for x in nums if x > 5]
    print(result)
    ```
    
    a) [6,7,8,9,10]  
    b) [1,2,3,4,5]  
    c) [5,6,7,8,9,10]

32. For tsikli va enumerate natijasi:
    ```python
    fruits = ['olma','banan','uzum']
    for i, fruit in enumerate(fruits, 1):
        print(f"{i}. {fruit}")
    ```
    
    a) 1. olma 2. banan 3. uzum  
    b) 0. olma 1. banan 2. uzum  
    c) olma banan uzum

33. Lambda va map funksiyasi:
    ```python
    numbers = [1,2,3]
    result = list(map(lambda x: str(x)*2, numbers))
    print(result)
    ```
    
    a) ['11','22','33']  
    b) [2,4,6]  
    c) ['1','2','3']

34. Set metodi natijasi:
    ```python
    s = {1,2,3,4}
    s.discard(5)
    print(s)
    ```
    
    a) {1,2,3,4}  
    b) Error  
    c) {1,2,3,4,5}

35. String metodlari:
    ```python
    text = "  Python  "
    print(text.strip().lower())
    ```
    
    a) python  
    b) Python  
    c) PYTHON

36. Dictionary comprehension va if:
    ```python
    nums = range(5)
    d = {x:x**2 for x in nums if x%2==0}
    print(d)
    ```
    
    a) {0:0, 2:4, 4:16}  
    b) {1:1, 3:9}  
    c) {0:0, 1:1, 2:4, 3:9, 4:16}

37. List bo'shatish:
    ```python
    lst = [1,2,3,4,5]
    first, *rest = lst
    print(rest)
    ```
    
    a) [2,3,4,5]  
    b) [1,2,3,4]  
    c) [1]

38. Set operatsiyasi:
    ```python
    s1 = {1,2,3}
    s2 = {3,4,5}
    print(s1.symmetric_difference(s2))
    ```
    
    a) {1,2,4,5}  
    b) {3}  
    c) {1,2,3,4,5}

39. Try-except va else:
    ```python
    try:
        x = 5/2
    except ZeroDivisionError:
        print("xato")
    else:
        print("ok")
    ```
    
    a) ok  
    b) xato  
    c) 2.5

40. Filter va lambda:
    ```python
    words = ['salom', 'dunyo', 'python', 'dasturlash']
    result = list(filter(lambda x: len(x) > 5, words))
    print(result)
    ```
    
    a) ['dasturlash']  
    b) ['salom', 'python']  
    c) ['dunyo']

41. String metodlari:
    ```python
    text = "python dasturlash"
    print(text.title())
    ```
    
    a) Python Dasturlash  
    b) PYTHON DASTURLASH  
    c) python dasturlash

42. List metodlari:
    ```python
    lst = [1,2,3,2,4,2,5]
    print(lst.count(2))
    ```
    
    a) 3  
    b) 2  
    c) 1

43. Dictionary metodi:
    ```python
    d = {'a':1, 'b':2}
    print(list(d.values()))
    ```
    
    a) [1,2]  
    b) ['a','b']  
    c) {'a':1, 'b':2}

44. While va break:
    ```python
    i = 1
    while True:
        if i > 5:
            break
        print(i)
        i += 1
    ```
    
    a) 1 2 3 4 5  
    b) 1 2 3 4 5 6  
    c) infinite loop

45. Set amalining natijasi:
    ```python
    s = {1,2,3}
    s.add(3)
    print(len(s))
    ```
    
    a) 3  
    b) 4  
    c) Error

46. List comprehension va map:
    ```python
    nums = [1,2,3,4]
    result = [x**2 for x in map(lambda x: x*2, nums)]
    print(result)
    ```
    
    a) [4,16,36,64]  
    b) [1,4,9,16]  
    c) [2,4,6,8]

47. String metodlari kombinatsiyasi:
    ```python
    text = "  pYtHoN  "
    print(text.strip().lower().capitalize())
    ```
    
    a) Python  
    b) PYTHON  
    c) python

48. Dictionary va get metodi:
    ```python
    d = {'a':1, 'b':2}
    x = d.get('c', 0) + d.get('a', 0)
    print(x)
    ```
    
    a) 1  
    b) 0  
    c) Error

49. For tsikli va range:
    ```python
    total = 0
    for i in range(0,5,2):
        total += i
    print(total)
    ```
    
    a) 6  
    b) 10  
    c) 4

50. List va sort metodi:
    ```python
    lst = [(2,'b'), (1,'a'), (3,'c')]
    lst.sort(key=lambda x: x[1])
    print(lst)
    ```
    
    a) [(1,'a'), (2,'b'), (3,'c')]  
    b) [(2,'b'), (1,'a'), (3,'c')]  
    c) [(3,'c'), (2,'b'), (1,'a')]

51. Generator expression:
    ```python
    g = (x**2 for x in range(3))
    print(list(g))
    ```
    
    a) [0,1,4]  
    b) [1,4,9]  
    c) (0,1,4)

52. Set va for tsikli:
    ```python
    s = {1,2,3}
    result = set()
    for i in s:
        result.add(i*2)
    print(result)
    ```
    
    a) {2,4,6}  
    b) {1,2,3}  
    c) [2,4,6]

53. List va extend metodi:
    ```python
    lst1 = [1,2,3]
    lst2 = [4,5]
    lst1.extend(lst2)
    print(lst1)
    ```
    
    a) [1,2,3,4,5]  
    b) [1,2,3,[4,5]]  
    c) [[1,2,3],[4,5]]

54. Dictionary va items metodi:
    ```python
    d = {'a':1, 'b':2}
    for k,v in d.items():
        print(k+str(v), end=' ')
    ```
    
    a) a1 b2  
    b) ab12  
    c) 1 2

55. String va replace metodi:
    ```python
    text = "python python python"
    print(text.replace('python', 'java', 2))
    ```
    
    a) java java python  
    b) java java java  
    c) python python python

56. List va copy:
    ```python
    lst1 = [1,[2,3],4]
    lst2 = lst1.copy()
    lst1[1][0] = 5
    print(lst2[1])
    ```
    
    a) [5,3]  
    b) [2,3]  
    c) [1,2,3]

57. Function va default parametr:
    ```python
    def add(x,y=2):
        return x+y
    print(add(3))
    ```
    
    a) 5  
    b) 3  
    c) Error

58. Dictionary comprehension va zip:
    ```python
    keys = ['a','b','c']
    values = [1,2,3]
    d = {k:v for k,v in zip(keys,values)}
    print(d)
    ```
    
    a) {'a':1,'b':2,'c':3}  
    b) ['a1','b2','c3']  
    c) {('a',1),('b',2),('c',3)}

59. List va insert metodi:
    ```python
    lst = [1,2,3]
    lst.insert(1,lst.pop())
    print(lst)
    ```
    
    a) [1,3,2]  
    b) [3,1,2]  
    c) [1,2,3]

60. Try-except va finally:
    ```python
    try:
        print(1/0)
    except:
        print("error")
    finally:
        print("done")
    ```
    
    a) error done  
    b) done  
    c) error

61. While va continue operatori:
    ```python
    i = 0
    count = 0
    while i < 5:
        i += 1
        if i == 3:
            continue
        count += 1
    print(count)
    ```
    
    a) 4  
    b) 5  
    c) 3

62. Set va frozenset:
    ```python
    s = frozenset([1,2,3])
    s.add(4)
    print(s)
    ```
    
    a) AttributeError  
    b) {1,2,3,4}  
    c) frozenset({1,2,3,4})

63. Dictionary update metodi:
    ```python
    d1 = {'a':1, 'b':2}
    d2 = {'b':3, 'c':4}
    d1.update(d2)
    print(d1)
    ```
    
    a) {'a':1, 'b':3, 'c':4}  
    b) {'a':1, 'b':2, 'c':4}  
    c) {'a':1, 'b':2}

64. List va index metodi:
    ```python
    lst = [1,2,3,2,4]
    print(lst.index(2, 2))
    ```
    
    a) 3  
    b) 1  
    c) 2

65. String metodlari:
    ```python
    text = "python-dasturlash-tili"
    print(text.split('-'))
    ```
    
    a) ['python', 'dasturlash', 'tili']  
    b) 'python dasturlash tili'  
    c) ['python-dasturlash-tili']

66. Lambda va filter:
    ```python
    numbers = range(10)
    result = list(filter(lambda x: x>5 and x<8, numbers))
    print(result)
    ```
    
    a) [6,7]  
    b) [5,6,7,8]  
    c) [6,7,8]

67. Set operatsiyalari:
    ```python
    s1 = {1,2,3}
    s2 = {3,4,5}
    print(s1 | s2)
    ```
    
    a) {1,2,3,4,5}  
    b) {3}  
    c) {1,2,4,5}

68. List comprehension va enumerate:
    ```python
    words = ['a', 'b', 'c']
    result = [f"{i}:{v}" for i,v in enumerate(words)]
    print(result)
    ```
    
    a) ['0:a', '1:b', '2:c']  
    b) ['a', 'b', 'c']  
    c) [0, 1, 2]

69. Dictionary va pop metodi:
    ```python
    d = {'a':1, 'b':2, 'c':3}
    value = d.pop('b', 0)
    print(d)
    ```
    
    a) {'a':1, 'c':3}  
    b) {'a':1, 'b':2, 'c':3}  
    c) {'a':1, 'c':3, 'b':0}

70. String formatlash:
    ```python
    name = "Python"
    version = 3.9
    print("%s %.1f" % (name, version))
    ```
    
    a) Python 3.9  
    b) Python3.9  
    c) Python 3

71. List va remove metodi:
    ```python
    lst = [1,2,3,2,4]
    lst.remove(2)
    print(lst)
    ```
    
    a) [1,3,2,4]  
    b) [1,2,3,4]  
    c) [1,3,4]

72. Function va args:
    ```python
    def sum_all(*args):
        return sum(args)
    print(sum_all(1,2,3))
    ```
    
    a) 6  
    b) [1,2,3]  
    c) Error

73. Set va issubset:
    ```python
    s1 = {1,2}
    s2 = {1,2,3,4}
    print(s1.issubset(s2))
    ```
    
    a) True  
    b) False  
    c) None

74. Dictionary va setdefault:
    ```python
    d = {'a':1}
    d.setdefault('b', 2)
    print(d)
    ```
    
    a) {'a':1, 'b':2}  
    b) {'a':1}  
    c) Error

75. Generator funksiya:
    ```python
    def get_numbers(n):
        for i in range(n):
            yield i*2
    print(list(get_numbers(3)))
    ```
    
    a) [0,2,4]  
    b) [1,2,3]  
    c) [2,4,6]

76. List bo'shatish:
    ```python
    lst = [1,2,3,4,5]
    a, *b, c = lst
    print(b)
    ```
    
    a) [2,3,4]  
    b) [1,2,3]  
    c) [3,4,5]

77. List sort metodining natijasi:
    ```python
    numbers = [(1,'b'), (2,'a'), (0,'c')]
    numbers.sort(key=lambda x: x[1])
    print(numbers)
    ```
    
    a) [(2,'a'), (1,'b'), (0,'c')]  
    b) [(1,'b'), (2,'a'), (0,'c')]  
    c) [(0,'c'), (1,'b'), (2,'a')]

78. Set metodi natijasi:
    ```python
    s1 = {1,2,3,4}
    s2 = {3,4,5,6}
    print(s1 - s2)
    ```
    
    a) {1,2}  
    b) {5,6}  
    c) {1,2,5,6}

79. Dictionary comprehension:
    ```python
    letters = ['a','b','c']
    d = {x:ord(x) for x in letters}
    print(d['a'])
    ```
    
    a) 97  
    b) 65  
    c) 1

80. String metodlari:
    ```python
    text = "python#dasturlash#tili"
    print('#'.join(text.split('#')[:2]))
    ```
    
    a) python#dasturlash  
    b) dasturlash#tili  
    c) python#dasturlash#tili

81. Lambda funksiyasi:
    ```python
    func = lambda x,y: x if x>y else y
    print(func(5,3))
    ```
    
    a) 5  
    b) 3  
    c) True

82. List methodlari:
    ```python
    lst = [1,2,3,4,5]
    lst.reverse()
    print(lst[1:4])
    ```
    
    a) [4,3,2]  
    b) [2,3,4]  
    c) [5,4,3]

83. Function va kwargs:
    ```python
    def print_info(**kwargs):
        return len(kwargs)
    print(print_info(name="John", age=25))
    ```
    
    a) 2  
    b) 0  
    c) Error

84. Tuple va list:
    ```python
    t = (1,2,[3,4])
    t[2][0] = 5
    print(t)
    ```
    
    a) (1,2,[5,4])  
    b) TypeError  
    c) (1,2,[3,4])

85. Dictionary va get metodi:
    ```python
    d = {'a':1, 'b':2}
    x = d.get('c', [3,4])
    print(x)
    ```
    
    a) [3,4]  
    b) None  
    c) KeyError

86. List comprehension va zip:
    ```python
    x = [1,2,3]
    y = [4,5,6]
    result = [a+b for a,b in zip(x,y)]
    print(result)
    ```
    
    a) [5,7,9]  
    b) [1,2,3,4,5,6]  
    c) [(1,4),(2,5),(3,6)]

87. String metodlari:
    ```python
    text = "Python Dasturlash"
    print(text.swapcase())
    ```
    
    a) pYTHON dASTURLASH  
    b) PYTHON DASTURLASH  
    c) python dasturlash

88. Set va frozenset:
    ```python
    s = {1,2,3}
    f = frozenset([2,3,4])
    print(s & f)
    ```
    
    a) {2,3}  
    b) {1,4}  
    c) {1,2,3,4}

89. Dictionary va pop metodi:
    ```python
    d = {'a':1, 'b':2}
    value = d.pop('c', -1)
    print(value)
    ```
    
    a) -1  
    b) KeyError  
    c) None

90. Generator expression:
    ```python
    gen = (x**2 for x in range(3))
    for i in gen:
        print(i, end=' ')
    ```
    
    a) 0 1 4  
    b) 1 4 9  
    c) 0 1 2

91. Function va return:
    ```python
    def func(x):
        if x < 0:
            return
        return x
    print(func(-1))
    ```
    
    a) None  
    b) -1  
    c) 0

92. List va extend:
    ```python
    lst = [1,2]
    lst.extend('34')
    print(lst)
    ```
    
    a) [1,2,'3','4']  
    b) [1,2,34]  
    c) [1,2,'34']

93. Set metodlari:
    ```python
    s1 = {1,2,3}
    s2 = {3,4,5}
    print(s1.symmetric_difference(s2))
    ```
    
    a) {1,2,4,5}  
    b) {3}  
    c) {1,2,3,4,5}

94. String formatlash:
    ```python
    num = 42
    text = f"Answer: {num:03d}"
    print(text)
    ```
    
    a) Answer: 042  
    b) Answer: 42  
    c) Answer: 00042

95. List va slicing:
    ```python
    lst = [1,2,3,4,5]
    lst[1:4] = [0]
    print(lst)
    ```
    
    a) [1,0,5]  
    b) [1,0,3,4,5]  
    c) [1,2,0,4,5]

96. Dictionary va default qiymat:
    ```python
    from collections import defaultdict
    d = defaultdict(list)
    d['a'].append(1)
    print(dict(d))
    ```
    
    a) {'a': [1]}  
    b) {'a': 1}  
    c) KeyError

97. Function va lambda:
    ```python
    def apply(f, x):
        return f(x)
    result = apply(lambda x: x*2, 5)
    print(result)
    ```
    
    a) 10  
    b) 5  
    c) lambda

98. List va sort metodi:
    ```python
    words = ['python', 'kod', 'dastur']
    words.sort(key=len)
    print(words)
    ```
    
    a) ['kod', 'dastur', 'python']  
    b) ['python', 'dastur', 'kod']  
    c) ['dastur', 'python', 'kod']

99. Generator funksiya:
    ```python
    def countdown(n):
        while n > 0:
            yield n
            n -= 1
    print(list(countdown(3)))
    ```
    
    a) [3,2,1]  
    b) [1,2,3]  
    c) [3,2,1,0]

100. Dictionary va items:
    ```python
    d = {'x': 1, 'y': 2}
    print(list(d.items())[0])
    ```
    a) ('x', 1)  
    b) 'x'  
    c) 1

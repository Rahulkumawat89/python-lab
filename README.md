s=input()
s
Rahul 123 9.2014
'Rahul 123 9.2014'
name=input("Enter your name : ")
print("Hello!!",name)
Enter your name : more
Hello!! More
num=input("Enter a number : ")# This code will not work as the num is by default of str type
print(num+100)
100 
Enter a number: 58
str
n = int(input('Enter a number: '))
print(n + 100)
Enter a number: 50
150
fname= "rahul"
lname="kumawat"
print("Name :",fname,lname)
Name : rahul kumawat
type(len)
builtin_function_or_method
print('rahul kumawat',19,'ci')
Rahul kumawat 19 ci
print('rahul kumawat',19,'ci',sep='/')
Rahul kumawat/19/ci
print('rahul kumawat',19,'ci',sep='...')
Rahul kumawat...19...ci
d={'rohit':8,'rahul':2,'kumawat':3}
for k,v in d.items():
  print(k,v,sep=' -> ')
Rohit -> 8
Rahul -> 31
Kumawat -> 35
print('rahul kumawat',19,'ci',sep='') #So we can say thet the by default sep=' '
Rahul kumawat19ci
print('rahul')
print(19)
print('ci')
Rahul
19
ci
print('rahul', end='/')
print(19, end='/')
print('ci')
Rahul/19/ci
print('rahul\n',19,'\n','ci',sep='',end='') #So we can say that default value of end='\n'
Rahul
19
ci
for n in range(10):
  print(n)
0
1
2
3
4
5
6
7
8
9
for n in range(10):
  print(n, end=' ')
0 1 2 3 4 5 6 7 8 9 
print('%d %s cost Rs%.2f' % (6, 'bananas', 1.74))
6 bananas cost Rs1.74
print('Hello, my name is %s.' % 'rahul')
Hello, my name is rahul.
txt = "welcome to the csit department"
x = txt.split()  #The split() method splits a string into a list.
x
['welcome', 'to', 'the', 'csit', 'department']
#string.split(separator, maxsplit)
txt = "hello, my name is rahul, I am 20 years old"
x = txt.split(", ")
print(x)
['hello', 'my name is rahul', 'I am 20 years old']
txt = "apple#banana#cherry#orange"
x = txt.split("#")
print(x)
['apple', 'banana', 'cherry', 'orange']
txt = "apple#banana#cherry#orange"
# setting the maxsplit parameter to 1, will return a list with 2 elements!
x = txt.split("#", 1)
print(x)
['apple', 'banana#cherry#orange']

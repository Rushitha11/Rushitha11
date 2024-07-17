# Rushitha11
#program replace all the vowels with *(star) in the string "hello world"
str_='python selenium'
in_=0
ne_s=''
while in_<len(str_):
    if str_[in_] in 'AEIOUaeiou':
        ne_s=ne_s + '*'
    else:
        ne_s=ne_s + str_[in_]
 #write a program to check if the given list of the strings which is polindrom
elements=input("enter some elements:\n").split()
i=0
l_=[]
while i<len(elements):
    if elements[i]==elements[i][::-1]:
        l_+=[elements[i]]
    i+=1
print(l_)
                  or
elements=input("enter some elements:\n").split()
i=0
while i<len(elements):
    if elements[i]==elements[i][::-1]:
        print(elements[i], end='')
    i +=1
 #data=[hi,hello,10,'12.3',12,19,6.2] program to get only integers from the list
l1=['hai','hello','12.3',10,19,6.2]
i=0
while i<len(l1):
    if type(l1[i])==int:
        print(l1[i])
    i +=1
i=0
while i<len(l1):
    if isinstance(l1[i],int):
        print(l1[i])
    i+=1
#program to iterate any iterable
str_='python'
for i in str_:
    print(i)
list_=['python','java','perl','css',45,2.4]
for i in list_:
    print(i)

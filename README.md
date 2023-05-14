# HW_2
name = 'Maksym'
surname = 'Slipchenko'
print(f'Nmame: {name}, Surname: {surname}')
print('Name: {}'.format(name))
print('Full name: {} {}'.format(name, surname))
print('Full name: {1} {0}'.format(name, surname))

print('*' * 40)

string = 'Gad fgdh hty'
a = string.split(' ')
b = string.upper()
c = string.lower()
d = string.capitalize()
e = string.find('fg')
print(f'{a}\n{b}\n{c}\n{d}\n{e}\n')

print('*' * 40)

list1 = ['first', 'third']
list2 = ['a', 'b']
new_list = list1.copy()
list1.append('fourth')
list1.insert(1, 'second')
print(list1)
print(new_list)

l1 = ['1', '2']
l2 = ['3', '4']
l3 = l1 + l2
l1.extend(l2)
print(l3)
print(l1)

list = ['a', 'b', 'c', 'd', 'e']
list.pop()
list.pop(1)
list.remove('a')
print(list)
print(list[1])

print('*' * 40)

string1 = 'hello'
list_1 = ['1', '2', '3', '4', '5', '6', '7', '8']
x = string1[::-1]
n = list_1[::-1]
m = list_1[1:7:2]
k = string1[1:3]
print(f'{x}\n{n}\n{m}\n{k}\n')

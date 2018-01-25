***�ı�Ϊ��python���׽̡̳�����ѧ�ʼ�***


#   **��һ��**

###    **ʹ�ý�����ʾ��**
��Python���������ʾ�����룺
            
```python
print("Hello World!");
```

���

![01.png](img/01.png "")



### **����˳���������ʾ��**
>    GNU/LINUX ���� OS X�ϵ�shell����`ctrl+d' �������� `exit()`

>    WINDOWS: `ctrl+z [enter]` �˳�


### **ʹ�ñ༭��**

����ʹ����pycharm

![02.png](img/02.png "")


---
#    **����**


### **ע��**
���ӣ�

        
```python
print('Hello world') # print is a function
```
   
   
### **���泣��**

>    ���泣��������������23 4 ���������ֻ���`����һ���ı�` �������ı�


### **����**

>    ������Ҫ������
>    *    ����(Integers)
>    *    ������(Floats)


### **�ַ���**

>�ַ���(string) ���ַ�(characters)������(sequence)
>    *    ������,����ʹ�õ�������ָ���ַ���,����˵`'���������������'`
>    *    ˫����,��˫���ź͵��������������ַ����乤��������һ����,����˵`"what's your name?`
>    *    ������,��������֮���ʵ�����Ƕ����ַ��������������������֮�����ɵ�ʹ�õ����ź�˫����        


### **�ַ����ǲ��ɱ��**

����ζ��һ���㴴����һ���ַ�������Ͳ��ܸı���


###  **��ʽ������**

��ʱ���������������Ϣ�й����ַ���������formate����

```python
age = 20
name = 'chenpeng'
print('{0}' was {1} years old when he wrote this book.'.format(name,age))
print('why is {0} playing with that python?'.format(name))
```

���н����

![03.png](img/03.png "")

���ǣ������ǿ�ѡ�ģ�ͬ����Ҳ����д��

```python
print('{} was {} years old when he wrote this book'.format(name,age))
print('why is {} playing that with python?'.format(name))
```

formate ���и���ϸ���÷���

```python
        # ���ڸ�������'0.333' ����С����(.)����λ
        print('{0:.3f}'.format(1.0/3));
        # ʹ���»�������ı������������ִ����м�λ��
        # ʹ��(^)����'___hello___'�ַ�������Ϊ11
        print('{0:_^11}'.format('hello'))
        #���ڹؼ������'Swaroop wrote A Byte of Python
        print('{name} wrote {book}'.format(name="xiaopeng",book="enjoy-python"))
```
        
ע��print()������������һ�����ɼ���"��һ��"�ַ�(\n)��β,Ϊ�˷�ֹ��ӡ�����г���
����,����ͨ��`end`ָ���հ׽�β:

```python
        print('a',end='')
        print('b',end='')
```
        
������:

        ab
        
���������ͨ��endָ���ո��β:

```python
        print('a',end=' ')
        print('b',end=' ')
        print('c')
```
        
������:

        a b c


###    **ת������(Escape Sequence)**

���ϣ�����ɵ��ַ����а���(')��(\)�Լ�������������ַ�����ʽ��(\n)��(\t)����Ҫ�õ�ת������

����Ҫ���`what's your name` 

Ӧ������д `'what\'s your name'`

����`\n`����,`This is the first line \n This is the second line'`

����һ��������÷�������ĩβ��ʾ�ַ�������һ�м���:

```python
        "This is the first sentence.\
        This is the second sentence."
```

�൱��:

```python
        "This is the first sentence.This is the second sentence."
```
     

###    **ԭʼ�ַ���**

�������Ҫָ��һЩδ��������ַ���,����ת������,�������ַ���ǰ����`r`����`R`

```python
        r"Newlines are indicated by \n"
```

    
###    **����**

ʹ���������޷��������ǿ��������� ��ʱ�����Ҫʹ�ñ���(veriables).


###    **��ʶ������**

*    ��һ���ַ���������ĸ���е���ĸ(��СдASCII����Unicode����_)
*    ��ʶ�����������ֿ����ַ����»��ߡ��������
*    ��ʶ�����ִ�Сд


###    **��������**

�������Խ�������ʽ��ֵ����Ϊ��ͬ����������,�������������Ͱ������ֺ��ַ������ں������ǽ�������ͨ����(Classes)�����������Լ�����������.


###    **����**

��Ҫ��סpython���������κ�����ͳ��Ϊ����(Object).����һ������Ľз�������ͨ����ĳ����(object)��ƣ�����ĳ����(something)


###     **��α�дpython����**

������ʹ�ñ������������
 
```python
# �ļ���:var.py

i = 5
print(i)
i = i+1
print(i)

s = '''This is muti-line string.
This is the second line.'''
print(s)
```

�����

        5
        6
        This is muti-line string.
        This is the second line.
        
>    �������򱻸�ֵĳһ��ֵ������Ҫ����������������


###    **���������߼���**

������(Physical Line)��ָ�ڱ�д����ʱ�������������ݡ�
�߼���(Logical Line)��ָPython��ʶ��ĵ�����䡣
ʵ���ϣ�python��������һ����������ÿһ��ʹ��һ����������Ӷ�ʹ�ô�����ӿɶ�
�����ϣ����һ����������ָ�������߼��У���ô�����ʹ��`;`����ʾ���л������Ľ���.

```python
i = 5
print(i)
```
ʵ���ϵȼ���
```python
i = 5;
print(i);
```
ͬ�����Կ���
```python
i = 5;print(i);
```
Ҳ����һд����ͬ
```python
i = 5;print(i)
```
> ʵ���ϲ�Ӧ��ʹ�÷ֺţ���python�����д�಻����`;`��ʹ�ã��������һ�зǳ����Ĵ��룬�����ͨ����б��`\`�������ֳɶ��������.�ⱻ��֮Ϊ**��ʽ����**(Explicit Line Joining):

```python
s = 'This is a string.\
This continues the string.'
print(s)
```
��������

        This is a stirng.This continues the string.
        
���Ƶأ�

```python
i = \
5
```
�ȼ���
```python
i = 5
```

>    ��ĳЩ����£������һ�������Ľ��棬�����㲻�÷�б����һ����������ſ�ʼ���������Ƿ����Ż��߻����ţ��������ǽ������ţ����Ϊ**��ʽ����**(Implicit Line Joining)


### **����**

�հ�����python���Ƿǳ���Ҫ�ġ��հ����ڸ��еĿ�ͷ�ǳ���Ҫ����Ϊ(Indentation).���߼��еĿ�ͷ���¿հ���(ʹ�ÿո�����Ʊ��)����ȷ�����߼��е��������𣬺��߿���ȷ�����ķ��顣���ʾ������һ���������Ҫ����ͬ�����������ǰ�ÿһ������������Ϊ**��**(block)

����������ᵼ�´���

```python
i = 5
 print('Value is',i)
print('I repeat,the value is',i)
```
![04.png](img/04.png "")


>�������?

>ʹ���ĸ��ո�������������python�ٷ��Ľ���


---
#    **���������ʽ**



��������д�Ĵ�������(�߼���)�������˱��ʽ(Expressions).
һ�����ʽ�ļ򵥵����Ӿ���`2+3`.���ʽ�����Բ��Ϊ
*    �����(Operators)
*    ������(Operands)

��`2+3`�����ı��ʽ�`+`�����������`2`��`3`���ǲ�����


###    **�����**

��������Ҫ���˽����������Լ����ǵ��÷�

![05.png](img/05.png "")

�����������������

*    `+` ���ӣ�
        *    �����������
        *    `3+5`�����`8`��`'a'+'b'` ��� `'ab'` 

        
*    `-` ������
        *    ��һ�����м�ȥ��һ����,�����һ�������������ڣ��ٶ�Ϊ0
        *    `-5.2` �����һ������
 
       
*    `*` ���ˣ�
        *    �����������ĳ˻������߷����ַ����ظ�ָ��������Ľ��
        *    `2*3` ��� `6` . `'la'*3` ��� `'lalala'`.
    
    
*    `**`���˷���
        *    ����x��y�η�
        *    `3**4` ��� `81` ����`3*3*3*3`��
     
   
*    `/` ������
        *    x����y
        *    `13/3` ��� `4.333333333333`


*    `//` ��������
        *    x����y���Խ������ȡ������ӽ�������
        *    `13//4` ��� `4`.
        *    `-13//4` ��� `-5`
       

*    `%` ��ȡģ��
        *    ���س���֮�������
        *    `13%5` ��� `1` 


*    `<<` �����ƣ�
        *    �����ֵ�λ�����ƶ�ָ����λ��
        *    `2<<2` ��� `8` 


*    `>>` �����ƣ�
        *    �����ֵ�λ�����ƶ�ָ����λ��
        *    `11>>1` ��� `5`


*    `&` ����λ�룩
        *    �����ֽ��а�λ�����
        *    `5&3` ��� `1`


*    `|` ����λ��
        *    �����ֽ��а�λ�����
        *    `5|3` ��� 7


*    `~` ����λȡ����
        *    `~5` ��� -6 
        *    x��ȡ���Ľ��Ϊ `-(x+1)`


*    `<` ��С�ڣ�
        *    ����x�Ƿ�С��y�����бȽϵĽ������`True`����`False`��ע������ĸΪ��д
        *  `5<3` ��� `False`
        *  �ȽϿ��������������:`3<5<7` ���� `True`


*    `<=` ��С�ڵ��ڣ�
        *    ����x�Ƿ�С�ڻ����y
        *    `x = 3;y = 6;x<=y` ���� `True`


*    `>=` �����ڵ��ڣ�
        *    ����x�Ƿ���ڻ��ߵ���y
        *    `x = 4;y = 3;x>=3` ���� `True`


*    `==` �����ڣ�
        *    �Ƚ����������Ƿ����
        *    `x = 2;y = 2;x == y` ���� `True`
        *    `x = 'str';y = 'stR';x == y` ���� `False`
        *    `x = 'str';y = 'str';x == y` ���� `True`


*    `!=` �������ڣ�
        *    �Ƚ����������Ƿ����
        *    `x = 2;y = 3;x!=y` ���� `True`


*    `not` ������"��"��
        *    ���x��`True`,���� `False`��ͬ��֮������
        *    `x = True;not x` ���� `False`


*    `and` ������"��"��
        *    ��xΪ`False`,��` x and y `���� `False`,���򷵻�`y`�ļ���ֵ
        *    ��xΪ`False`,` x = False;y = True; x and y `��ʱpython���������y��Ϊ���Ѿ��˽�and���ʽ�����Ϊ`False`����ζ���������ʽ����`False`,�������Ϊ**��·����**(Short-circuit Evaluation)


*    `or` ������"��"��
        *    ���xΪ` True `,���� ` True `�����򷵻�y�ļ���ֵ
        *    ` x = True;y = False; x or y ` ����` True `,�������·����ͬ������.
   

### **��ֵ�����븳ֵ�Ŀ�ݷ�ʽ**

> ���� = ���� ���� ���ʽ 

``` python
a = 2
a = a*3
```

> ���� ���� = ���ʽ 

```python
a = 2
a *= 3
```

### **��ֵ˳��**

�±�������python����������ȼ�

![yunsuan01.png](img/yunsuan01.png "")
![yunsuan02.png](img/yunsuan02.png "")

  
### **�ı�����˳��**

����ʹ��������ʹ�ñ��ʽ�����׶�


### **�����**

�����ͨ���������ҽ��


### **���ʽ**

����

```python
length = 5
breadth = 2

area = length*breadth
print('Area is ',area)
print('Perimeter is ',2*(length+breadth))
```

���

  ![ex.png](img/ex.png "")
  


---
#    **������**

python�������ֿ��������
*    if
*    for
*    while


### **if���**

����������else�Ӿ��ǿ�ѡ��

```python
number = 23
guess = int(input('Enter an integer:'))

if guess == number:
    print('Congratulations,gu guessed it.')
    print('(but you do not win any prizes!)')
elif guess<number:
    print("No,it is a litter higher than that")
else:
    print('No,it is a little lower than that!')

print('Done')
```

���

![cg.png](img/cg.png "")
![lr.png](img/lr.png "")


> python �в�����switch���


### **while ���**

������

```python
number = 23
running = True

while running:
    guess = int(input('enter an integer :'))

    if guess == number:
        print('success!,you guessed it.')
        running = False
    elif guess<number:
        print('No,it is little higher!')
    else:
        print('No,it is little lower!')
else:
    print('The while loop is over.')

print('done')
```

�����

![while-01.png](img/while-01.png "")

> ������whileѭ����ʹ��else���


### **for ѭ��**

```python
for i in range(1,5):
    print(i)
else:
    print('The for loop is over')

```
����Ľ��Ϊ

![for.png](img/for.png "")

>���������������ʹ�������õ�`range`����������һ�������С�range(1,5)�������[1,2,3,4]�����������range�ṩ������������������ֽ���Ϊ����������range(1,5,2),�������[1,3],�ر�ע�ⲻ�����ڶ����������ڣ�������ѧ������������߿����䣬�ұ߱����䣬��������Ϊ������



### **break ���**


`break`��������ж�ѭ����䣬Ҳ������ֹѭ������䡣

> ��һ����Ҫע����ǣ�������ж��˱���for��whileѭ������ô���κ���Ӧѭ���е�else�鶼������ִ��

������

```python
while True:
    s = input('Enter something:')
    if s == 'quit':
        break
    print('Length of the string is ',len(s))
print('Done')
```
���н����

![break.png](img/break.png "")


###  **continue ���**

��νcontinue���Ǹ���python������ǰѭ���е�ʣ�����������һ��ѭ����

������

```python
while True:
    s = input('Enter something:')
    if s == 'quit':
        break
    if len(s)<3:
        print('Too small')
        continue
    print('Input is out of sufficient length')
```

���н����

![continue.png](img/continue.png "")

> ע�� continue ͬ���ܹ�������forѭ��



#    **����**

��ν����(Functions)���ǿ��ظ�ʹ�õĳ���Ƭ�Ρ�
ͨ���������ڳ�����κεط������д���飬���ҿ���ִ������������������ν�ĵ���(Calling)����

��������ͨ��`def` ������
> ����������ʽ:

        def say_hello():
            # do something...
        # end function
>�����ĵ���:  

        say_hello() 
        


### **��������**

�����еĲ���ͨ����ֹ�����Զ��庯����һ��������ָ����

�ر�أ�

**�ڶ��庯��ʱ��������ƽ���"�β�"(Parameters)**

**�ڵ��ú���ʱ���ṩ��������ֵ��Ϊ"ʵ��"(Arguments)**

������

```python
def print_max(a,b):
    if a>b:
        print(a,'is maximum')
    elif a == b:
        print(a,'is equal to',b)
    else:
        print(b,'is maximum')


print_max(3,4)

x = 5
y = 7

print_max(x,y)
```

���н����

![function.png](img/function.png "")

> ��һ�ε���������ʵ�ε���ʽֱ�������ṩ��һ���֣��ڶ��ε���ʱ������ʹ�ñ�������Ϊʵ�ε��ú������ǵĽ�ʵ��x��ֵ���β�a������print_max������ͬ�ķ�ʽ����


### **�ֲ�����**

> ������һ�������Ķ������������������ǲ������κη�ʽ��������֮�������ͬ���Ƶı��������κεĹ�ϵ��Ҳ����˵����Щ��������**ֻ���ں�����һ�ֲ�(local)**.�ⱻ��֮Ϊ**������(Scope)**.

����:

```python
x = 50

def func(x):
    print('x is ',x)
    x = 2
    print('Changed local x to ',x)

func(x)
print('x is still ',x)
```

�����

![function_local.png](img/function_local.png "")

> ʵ����x��ֵ�������յ����õĺ����еľֲ�������Ӱ��.


### **`global` ���**


��������һ���ڳ��򶥲�ı�����ֵ����������python����һ��ȫ��(Global)�ı������Ǿֲ�����,����ͨ����Ҫͨ��global���������������.��Ϊ���㲻��Ϊһ�������ں���֮��ı�����ֵ.

������

```python
x = 50

def func():
    global x

    print('x is ',x)
    x = 2
    print('changed global x to ',x)

func()
print('value of x is ',x)
```

���н����

![function_global.png](img/function_global.png "")

> ���ѿ�������һ�����Ӳ�ͬ�����x�Ѿ��ı���,�������в�֪һ��ȫ�ֱ��������������д `global x,y,z`



###   **Ĭ�ϲ���ֵ**

������Щ���������ϣ����һЩ������ѡ��ʹ��Ĭ��ֵ��������ں�������ʱ�򣬸���һ����ֵ�����(`=`)��Ϊ�����ƶ�Ĭ�ϵĲ���ֵ.

����:

```python
def say(message,times=1):
    print(message*times)

say('Hello')
say('World',5)
```

���н����

![function_default.png](img/function_default.png "")

> ע�⣡
> �ں����б��У�ӵ��Ĭ�ϲ���ֵ��������λ��û��Ĭ�ϲ���ֵ�Ĳ���֮ǰ.
> ������˵,def func(a,b = 5)�ǺϷ��ģ���def func(a = 5,b)����Ч��


### **�ؼ��ֲ���**

��������һЩ�������ĺ��������ǣ��㲻����Ϊÿһ����������ֵ��������������ɵ������ֻϣ��������ĳЩ�ؼ��Ĳ���������Щ������ֵ�������**�ؼ��ֲ���(*Keywrod Arguments*)**

������

```python
def func(a,b = 5,c =10):
    print('a is ',a,' and b is ',b,'and c is ',c)

func(3,7)
func(25,c = 24)
func(c = 50,a = 100)
```

���н����

![function_keyword.png](img/function_keyword.png "")

> ʵ���Ͽ��Կ���func(3,7),����a�����3������b���7����c����˺�������ʱ���Ĭ��ֵ
>�ڶ��ε��ã�����a���25��������ʱ�����ǲ����b��ֵ������ͨ���ؼ��ֲ�����ֱ�Ӹ�c��ֵ���Ӷ������˺�������ʱ����˳����޶�
>ͬ������ε��ã�����ֱ�ӽ�c�ȸ�ֵ���ٶ�a��ֵ����Ҳ������ģ�����python���﷨���Ǻ�����!��ס����**�ؼ��ֲ���**�������ǵı���


### **�ɱ����**

��ʱ������붨��ĺ��������ܹ������������ı�����Ҳ���ǲ��������ǿɱ�ģ������ͨ��ʹ���ͺ���ʵ��

������

```python
def total(a = 5,*numbers,**phonebook):
    print('a',a)

    for single_item in numbers:
        print('single_item',single_item)

    for first_part,second_part in phonebook.items():
        print(first_part,second_part)

print(total(10,1,2,3,Jack = 1123,John = 2231,Inge=1560))
```

�����

![function_varargs.png](img/function_varargs.png "")

> ����������\*param���ǺŲ���ʱ���Ӵ˴���ʼ֪������������λ�ò���(*Positional Arguments*)�������ռ����㼯��һ����Ϊ"param"��**Ԫ��(*Tuple*)**

> ����������\*\*param��˫�ǺŲ���ʱ,�Ӵ˴���ʱֱ�����������еĹؼ��ֲ����������ռ����㼯��һ����ΪParam��**�ֵ�(*Dictionary*)**


###     **`return` ���**

`return` ������ڴӺ����з��أ�Ҳ�����жϺ���.

������

```python
def maximum(x,y):
    if x>y:
        return x
    elif x == y:
        return "The numbers are equal "
    else:
        return y

print(maximum(2,3))
```

���н����

![function_return.png](img/function_return.png "")

> Ҫע�����return û�д����κ�һ��ֵ������� None.
None ��Pyton����һ����������ͣ����������ޡ�
ÿһ������������ĩβ������һ��`return None`,������д�����Լ���`return` ���.

> ������һ����Ϊmax���ú����Ѿ�ʵ���������ֵ�Ĺ��ܣ�������ʹ����һ���ú���



###    **DocStrings**

**DocStrings**��һ�����������Ĺ��ܣ��ܹ���������õؼ�¼�����������������⡣

������

```python
def print_max(x,y):
    '''prints the maximum of tow mumbers.
    The tow values must be integers.'''

    x = int(x)
    y = int(y)

    if x>y:
        print(x,' is maximum')
    else:
        print(y,' is maximum')

print_max(3,5)
print(print_max.__doc__)
```

�����

![function_docstring.png](img/function_docstring.png "")

>���ǿ���ͨ�������� `__doc__` ����������ȡ����print_max�ĵ����ַ������ԣ��Զ������߿��������ַ�ʽ������������е��ĵ�������ǽ�ѽ����д��������Ҫ�ĺ��������ĵ��ַ�����python���Ͱ汾�и�����pydoc�����help()ʹ���ĵ��ַ����ķ�ʽ����

---

#    **ģ��**

���������������д�ĳ���������һЩ�����Ļ���Ӧ����ô�죿����ģ��(Modules).

�����������˽����ʹ�ñ�׼��ģ��

```python
import sys

print('The command line arguments are:')
for i in sys.argv:
    print(i)

print('\n\nThe PYTHONPATH is ',sys.path,'\n')
```

�����

![module_using_sys.png](img/module_using_sys.png "")



### **���ֽڱ����.pyc�ļ�**

����һ��ģ����һ�����۸߰������飬���python������һЩ������ʹ���ܹ����ӿ��ٵ���ɡ�����һ�ַ�ʽ���Ǵ������ֽ�������***(byte-compiled)***�ļ�����Щ.pyc�ļ��Ƕ���������ƽ̨��

> ��Щ.pyc�ļ�ͨ���ᴴ���ڶ�Ӧ��.py�ļ�������Ŀ¼�У����pythonû����Ӧ��Ȩ�޶���һĿ¼����д���ļ��Ĳ�������ô.pyc�ļ������ᱻ����.



### **from..import ���**

���ϣ��ֱ�ӽ�argv�ı��������Լ��ĳ��򣬿���ʹ��`from sys import argv`��һ��������.

> ���棺һ����˵��Ӧ�þ�������ʹ��from...import ��䣬��ȥʹ��import���,����Ϊ�˱������Լ��ĳ����г������Ƴ�ͻ��ҲΪ��ʹ������ӵĿɶ�

����

```python
from math import sqrt
print('square root of 16 is ',sqrt(16))
```



### **ģ��� __name__���**

ÿһ��ģ�鶼��һ�����ƣ���ģ���е��������ҵ�����������ģ������ƣ������ȷ��ģ���Ƕ������еĻ��Ǳ�������������е���һ�ض�Ŀ����˵��Ϊ����.

������

```python
if __name__ == '__main__':
    print('This program is being run by itself')
else:
    print('Iam being imported from another module')

```

���

![module_using_name.png](img/module_using_name.png "")


###    **��д���Լ���ģ��**

��Python��ÿһ��python����ͬʱҲ��һ��ģ�顣ֻ��Ҫ��֤����.pyΪ��չ������

����(����Ϊ mymodule.py)

```python
def say_hi():
    print('Hi,this is mymodule speaking.')

__version__ = '0.1'
```

��һ��ģ��(����Ϊ mymodule_demo.py)

```python
import  mymodule

mymodule.say_hi()
print('Version',mymodule.__version__)

```

�����

        Hi,this is mymodule speaking.
        Version 0.1

������` from...import` �﷨�İ汾(����Ϊ `mymodule_demo2.py`)

```python
from mymodule import say_hi,__version__

say_hi()
print('Version',__version__)

```

> ������Ҫע����ǣ�������뵽mymodule���Ѿ�������\_\_version\_\_��һ���ƣ��ǽ��������ͻ���������Ǵ��Ƽ����ȥʹ��import ��䣬���ܿ�����������΢��һЩ��

�㻹����ʹ�ã�

```python
from mymodule import *
```
�⽫�������� `say_hi` �����й������ƣ������ᵼ��\_\_version\_\_����,��Ϊ������˫�»��߿�ͷ.

> ���棺Ӧ�ñ���ʹ��import-star ������ʽ



###    **dir ����**

���õ� `dir()` �����ܹ������ɶ���������������б�.
����ö�����һ��ģ��,����б�����������������ĺ������������

���⣬�ú��������ܲ������������ʱģ�����ƣ�������������һָ��ģ��������б����û���ṩ���������������ص�ǰģ��������б�

������

```python
import sys
dir(sys)
```

���صĽ����

![dir.png](img/dir.png "")

���������ǰģ�����������
```python
dir()
```

���صĽ��

![dir02.png](img/dir02.png "")

���Ŵ���һ���µı���

```python
a = 5
```

���صĽ����

![dir03.png](img/dir03.png "")

ɾ�������Ƴ�һ������

```python
del a
```

���صĽ����

![dir04.png](img/dir04.png "")

> ͬʱ����һ��` vars() `����Ҳ���Է��ظ�����Щֵ�����ԣ���ֻ�ǿ��ܣ����������е��඼����������

###    **��**

������������Ч�Ĺ���ѧ��java��c++��ͬ־��Ӧ��֪������������·����������һ��ɢɳ���ܹ���������������������ģ�����⡣python�У�����ͨ��λ�ں������ڲ���������ȫ�ֱ���ͨ��λ��ģ���ڲ��������ϣ����֯�����������**��(Package)**�ǳ���ʱ��.

����ָһ������ģ����һ���س���\_\_init\_\_.py�ļ����ļ��У�������Python������һ�ļ������ر�ģ���Ϊ�������pythonģ��.

�������봴��һ��"world"�İ������л�������"asia"��"afica"�Ȱ���������Щ�Ӱ�������������"india"��"madagascar"��ģ��.

        - <some floder present in the sys.path>/
            - world/
                - __init__.py
                - asia/
                    - __init_.py
                    - india/
                        - __init_.py
                        - foo.py
                - africa/
                    - __init__.py
                    - madagascar/
                        - __init__.py
                        - bar.py

> ����һ���ܹ�����طֲ���֯ģ��ķ�ʽ���㽫�ڱ�׼���п��������������ʵ��


---

#    **���ݽṹ**

���ݽṹ(Data Structures)�������洢һЩ������ݵļ��ϡ�

��python�����������õ����ݽṹ
*    �б�(List)
*    Ԫ��(Tuple)
*    �ֵ�(Dictionary)
*    ����(Set)

###    **�б�(List)**

�б���һ�����ڱ���һЩ**����**��Ŀ�ļ���.python����Ҫ��������֮������һ�����ţ���Ŀ���б�Ӧ���÷�����������������python�������������ָ��һ���б�.һ���㴴����һ���б��������ӡ�ɾ���������б��е���Ŀ.����˵�б���һ�ֿɱ�(Mutable)���������ͣ��������������ǿ��Ա��ı��.

###    **�йض������Ŀ��ٽ���**

�б���ʹ�ö��������ʵ��������������һ������i��������5��ֵ����ʱ���������Ϊ�����ڴ���һ��int��֮�µĶ���i.

һ����Ҳ���Դ��з���(Method),Ҳ����˵������ඨ�������������ĳ������.����python Ϊ list ���ṩ��һ�� append ����,���ܹ����������б�ĩβ���һ����Ŀ.����` mylist.append('an item') `������mylist���һ���ַ���.

һ����ͬ��Ҳ���Ծ����ֶ�(Field),����ֻΪ���ඨ����Ϊ�������õı���.�ֶ�ͬ������ͨ��.�����ʣ�����` mylist.field `.

����(����Ϊ ` ds_using_list.py `)

```python
shoplist = ['apple','mango','carrot','banana']

print('I have',len(shoplist),' items to purchase')

print('These items are:',end=' ')
for item in shoplist:
    print(item,end=' ')

print('\nI also have to buy rice.')
shoplist.append('rice')
print('My shopping list is now ',shoplist)

print('I will sort my list now')
shoplist.sort()
print('Sorted shopping list is ',shoplist)

print('The first item I will buy is ',shoplist[0])
olditem = shoplist[0]
del shoplist[0]
print('I bought the',olditem)
print('My shopping list is now',shoplist)

```

��������

![ds_using_list.png](img/ds_using_list.png "")

��������б�������κ����͵Ķ��󣬰������֣������������б�
���ǻ�ʹ�� for...in ѭ���������б��е�ÿһ����Ŀ
����ע���ڵ���print����ʱ����ʹ��end�������������ܹ�ͨ��һ���ո�������������������ͨ���Ļ���.
�����������������۵��ǶΣ�����ͨ���б�����е�append�������б������һ������.
>�б��ǿɱ�ģ����ַ����ǲ��ɱ��
��������Ҫɾ���б��е�Ԫ��ʱ������ʹ��`del`�����ʵ����һ����.

###    **Ԫ��**

Ԫ��(Tuple)���ڽ�������󱣴���һ���������б��ǲ����ṩ�б����ܹ��ṩ����Ĺ㷺�Ĺ��ܡ�Ԫ�ص�һ�������������ַ��������ǲ��ɱ�.�㲻�ܱ༭���߸���Ԫ��.

����(ds_using_tuple.py):

```python
zoo = ('python','elephant','penguin')
print('Number of animals in the zoo is ',len(zoo))

new_zoo = 'monkey','camel',zoo
print('Number of cages in the new zoo is ',len(new_zoo))
print('All animals in new zoo are ',new_zoo)
print('Animals brought from old zoo is ',new_zoo[2])
print('Last animal brought from old zoo is ',new_zoo[2][2])
print('Number of animals in the new zoo is ',len(new_zoo)-1+len(new_zoo[2]))
```

��������

![tuples.png](img/tuples.png "")

> ��ͬ�������б����������ǰ㣬���ǿ���ͨ���ڷ�������ָ����Ŀ������λ��������Ԫ���еĸ�����Ŀ������ʹ�÷����ŵ���ʽ����Ϊ**����(Indexing)**�����.
>
> һ���յ�Ԫ����һ��Բ������ɣ����� `myempty=()` ����.Ȼ����һ��ֻӵ��һ����Ŀ��Ԫ�沢����������.������ڵ�һ����Ŀ�ĺ�߼���һ��������ָ���������һ��python�ſ���ʶ�����������ʽ�������һ��Ԫ�黹��һ������.�������ָ��һ��������Ŀ2��Ԫ�������ָ��`singleton=(2,)`


###    **�ֵ�**

�ֵ����һ����ַ���������֪��ĳ�˵�������Ϳ����ҵ��Է�������ϸ����Ϣ�����ǽ���ֵ(Keys)��ֵ(Values)�໥��ϵ��һ��.��Ҫע����Ǽ�ֵ������Ψһ�ġ�

��Ҫ�ص�ע����ǣ���ֻ��ʹ�ò��ɱ�Ķ�����Ϊ�ֵ�ļ�ֵ��

���������ʹ�ÿɱ���߲��ɱ�Ķ�����Ϊ�ֵ��е�ֵ.

���ֵ��������ͨ��ʹ�÷��Ź��� ` d = {key:value1,key2:value2} ` ��������ʽ���ƶ���Ӧ�ļ�ֵ��.

���⣬���ֵ��гɶԵļ�ֵ�Բ������κη�ʽ��������.�����ϣ��Ϊ���ǰ���һ���ر�Ĵ���ֻ����ʹ������֮ǰ��������.

����(ds_using_dict.py)

```python
ab = {
    'Swaroop':'swarrop@swarroopch.com',
    'Larry':'larry@wall.org',
    'Matsumoto':'matz@ruby-lang.org',
    'Spammer':'spammer@hotmail.com'
}

print("Swaroop's address is ",ab['Swaroop'])

del ab['Spammer']

print('\n There are {} contacts in the address-book\n'.format(len(ab)))

for name,address in ab.items():
    print('Contact {} at {}'.format(name,address))

ab['Guido'] = 'guido@python.org'

if 'Guido' in ab:
    print("\nGuido's address is",ab['Guido'])

```

�����

![ds_using_dict.png](img/ds_using_dict.png "")


> ���ǿ���ͨ��������������ƶ�ĳһ����ֵ�Է�����Ӧ�ļ�ֵ���.

> ���ǿ���ͨ��` del `�����ɾ��ĳһ����ֵ-ֵ���.

> ͨ�� ` item `�����������ֵ��е�ÿһ�Լ�ֵ-ֵ�����Ϣ.

> ���������һ���µļ�ֵ-ֵ��ԣ����ǿ��Լ򵥵�ͨ��ʹ�����������������һ����ֵ��Ϊ֮������Ӧ��ֵ.

>���ǿ���ͨ��` in  `����������ĳ�Լ�ֵ-ֵ����Ƿ����.

> ����������ں�����ʹ�ù��ؼ��ֲ�������ô����Ѿ�ʹ�ù��ֵ��ˡ���������ĺ����з���ĳһ����ʱ������ʵ���Ƿ����ֵ��е�ĳ������.(�ڱ�������������У���������ű�[Symbol Table])


###    **����**

����(Sequence) �����ֱ�����ʽ:
*    �б�(List)
*    Ԫ��(Tuples)
*    �ַ���(Characters)


���е���Ҫ���ܣ�
*    �ʸ����(Membership Test) Ҳ���� ` in ` �� ` not in `���ʽ
*    ��������(Indexing Operations) �����ܹ���������ֱ�ӻ�ȡ�����е��ض���Ŀ


> �������ᵽ�����е�����״̬��ͬ����һ����Ƭ(Slicing)����������ܹ��������������е�ĳ����Ƭ--Ҳ���������е�һ����.


```python
shoplist = ['apple','mango','carrot','banana']

name = 'swaroop'

# indexing or 'subscription' operation
print('Item 0 is',shoplist[0])
print('Item 1 is',shoplist[1])
print('Item 2 is',shoplist[2])
print('Item 3 is',shoplist[3])
print('Item -1 is',shoplist[-1]) # banana
print('Item -2 is',shoplist[-2]) # carrot
print('Character 0 is',name[0])

# slicing on a list
print('Item 1 to 3 is',shoplist[1:3]) # [1,3)
print('Item 2 to end is',shoplist[2:]) # from index 2 to the end
print('Item 1 to -1 is',shoplist[1:-1]) # not included the last one ,because -1 equals 3(last one)
print('Item start to end is',shoplist[:]) #all

# slicing on characters
print('characters 1 to 3 is',name[1:3]) #[1,3)
print('characters 2 to end is',name[2:]) # from index 2 to the end
print('characters 1 to -1 is',name[1:-1]) # from index 1 to the last one(not included)
print('characters start to end is',name[:]) # all
```

��������

![ds_seq.png](img/ds_seq.png "")

> ��Ҫ�ر�ע���һ����Ƭ�����У������ǿ�ѡ�ģ�����ð��` : `ȴ����
> ��һ����������Ƭ��ʼ��λ�ã��ڶ���λ������Ƭ������λ�ã��ص�ǿ��������ʼ��λ�ã����ǲ�����������λ��


ͬ��������Ƭ�����л��ṩ�ĵ�������������������(Step)Ĭ�ϵĲ�����1

```python
>>>    shoplist = ['apple','mango','carrot','banana']
>>>    shoplist[::1]
['apple','mango','carrot','banana']
>>>    shoplist[::2]
['apple','carrot']
>>>    shoplist[::3]
['apple','banana']
>>>    shoplist[::-1]
['banana','carrot','mango','apple']
```

> ���е�һ���ŵ����������ʹ��ͬ���ķ�ʽȥ����Ԫ�桢�б��ַ���.


###    **����**

����(Set)�Ǽ򵥶�������򼯺�(Collection).

ͨ��ʹ�ü��Ͽ��Բ���ĳЩ������ʸ�����������������Ƿ����������ϵ��Ӽ�,�ҵ��������ϵĽ����ȵ�.


![set.png](img/set.png "")


###    **����**

���㴴����һ�����󲢽�ֵ��ĳ������ʱ�����������(Refer)ĳ������,������Ҳ������������.Ҳ����˵��������ֻ��ָ���������ڴ��д洢����Ӧ�������һ����.

����������ư�(Binding)����һ������.

����(ds_refrences.py)

```python
print('Simple Assignment')
shoplist = ['apple','mango','carrot','banana']

mylist = shoplist

del shoplist[0]

print('shoplist is ',shoplist)
print('mylist is ',mylist)

print('copy by making a full slice')
mylist = shoplist[:]

del mylist[0]

print('shoplist is ',shoplist)
print('mylist is ',mylist)
```

��������

![ds_reference.png](img/ds_reference.png "")

> ��Ҫ��ʾ�������ϣ������һ����Ѧ�ҵȸ��Ӷ���ĸ���ʹ����Ƭ�����
> ����������һ���������������һ������������ô���Ƕ������ͬһ�����������Դ˲���С�ģ���ô������ɺܴ���鷳.


###    **�й��ַ������������**

�ַ���Ҳ��һ�ֶ�����Ҳ���Լ��ܷḻ�ķ�����������������ַ����е�һ���֣�������ȥ���ո�ȼ���һ�е�����.

������ʹ���ַ����ľ��尸������ds_str_methods.py��

```python
name = 'Swaroop'

if name.startswith('Swa'):
    print('Yes,the string starts with "Swa"')

if 'a' in name:
    print('Yes,it contains the string "a"')

if name.find('war')!= -1:
    print('Yes,it contains the string "war"')

delimiter = '_*_'
mylist = ['China','Brazil','Russia','India']

print(delimiter.join(mylist))
```

��������

![ds_str_methods.png](img/ds_str_methods.png "")


> ` startswidth `���ڼ����ҵ��ַ��Ƿ����ַ����Ŀ�ͷ

> ` in ` ��������Լ��������ַ����Ƿ��ǲ�ѯ�ַ�����һ����

> ` find ` �������ڶ�λ�ַ����������ַ�����λ�á�����Ҳ�����Ӧ���ַ�����ô�ͻ᷵��-1

> ` str ` ��ͬ���Ļ���һ�����ķ���������(Join)�����е���Ŀ,�����ַ���������Ϊÿһ��Ŀ֮��ķָ���.

---

#    **�������**

�����Ѿ�ѧϰ��python���Եĺܶ��һ�����ˣ��������ǳ�������дһ��С������ʵսһ��.

###    **����**

>���������д����һ���������ܹ������ұ���������Ҫ���ļ�

������ϸ�����������������ν��?������Ҫ��һ���ķ�����
*    ����Ӧ�����ָ����Щ�ļ���������Ҫ���ݵ�?
*    ����Ӧ����α���?
*    ���ݺ���ļ���Ҫ�洢������?

������������ʼ������ǵĳ������������ǳ���Ӧ�������ת���嵥:
*    ��Ҫ���ݵ��ļ�����Ŀ¼Ӧ����һ���б�������ָ��
*    ���ݱ���洢��һ��������Ŀ¼��
*    �����ļ������ѹ����zip�ļ�
*    zipѹ���ļ����ļ����ɵ�ǰ���ں�ʱ�乹��
*    ����ʹ�����κ�GNU/Linux����Unix���а汾�ж���Ĭ���ṩ��׼��zip������д��

### **�������**

���������뱣��Ϊ backup_ver1.py:

```python
import os
import time

# 1.��Ҫ���ݵ��ļ���Ŀ¼����
# ָ����һ���б���
# ������windows��
# source = ['"C:\\My Documents"','c:\\Code']
# ����Mac OS X �� Linux�£�
source = ['E:\\Coding\\es6study']
# ��������Ҫ���ַ�����ʹ��˫���ţ������������а����ո������

# 2.�����ļ�����洢��һ��������Ŀ¼��
# ������windows �£�
# target_dir = 'E:\\Backup'
# �������� Mac OS X �� Linux �£�
target_dir = 'E:\\Testing'

# 3.�����ļ������ѹ����zip�ļ�
# 4.zipѹ���ļ����ɵ�ǰ������ʱ�乹��
target = target_dir+os.sep+\
    time.strftime('%Y%m%d%H%M%S')+'.zip'

# ���Ŀ��Ŀ¼�ļ���������Ҫ���д���
if not os.path.exists(target_dir):
    os.mkdir(target_dir)

# 5.������zip����ļ������zip��ʽ
zip_command = 'zip -r {0} {1}'.format(target,' '.join(source))

# ���б���
print('Zip command is :')
print(zip_command)
print('Running:')
if os.system(zip_command) == 0:
    print('Successful backup to',target)
else:
    print('Backup Failed!')
```
> �����ļ��������ɵ�ǰ������ʵ�����ɣ�����ͨ��`time.strftime()`����������
> ������Ҫע�� ` os.sep `��ʹ�÷�ʽ--����������Ĳ���ϵͳ������Ӧ�Ĳ�����
��GNU/Linux �� Unix ��������'/',��windows��������'\\',��Mac OS��������':'
> `time.strftime()`��������ѭĳЩ��ʽ
> ���ǿ���ʹ��`os.system`�����������һ��������ʹ�����������ϵͳ�����е�.


###    **�ڶ���**

�ڵ�һ���汾���Ѿ��ܹ����������ǻ���һ�����õ��ļ���������-ʹ��ʱ����Ϊ�ļ������洢���Ե�ǰ����Ϊ���ֵ��ļ����У���һ�ļ������ճ��洢��������Ŀ¼��.

```python
import os
import time

# 1.��Ҫ���ݵ��ļ���Ŀ¼����
# ָ����һ���б���
# ������windows��
# source = ['"C:\\My Documents"','c:\\Code']
# ����Mac OS X �� Linux�£�
# source = ['/users/swa/notes']
source = ['E:\\Coding\\es6study']
# ��������Ҫ���ַ�����ʹ��˫���ţ������������а����ո������

# 2.�����ļ�����洢��һ��������Ŀ¼��
# ������windows �£�
# target_dir = 'E:\\Backup'
# �������� Mac OS X �� Linux �£�
# target_dir = '/users/swa/backup'
target_dir = 'E:\\Testing'

# ���Ŀ��Ŀ¼�ļ���������Ҫ���д���
if not os.path.exists(target_dir):
    os.mkdir(target_dir)

# 3.�����ļ������ѹ����zip�ļ�
# 4.zipѹ���ļ����ɵ�ǰ������ʱ�乹��
today = target_dir+os.sep+time.strftime('%Y%m%d')
# ����ǰ��ʱ����Ϊzip�ļ����ļ���
now = time.strftime('%H%M%S')

# ZIP �ļ����Ƹ�ʽ
target = today+os.sep+now+'.zip'

# �����Ŀ¼�в������򴴽�һ��
if not os.path.exists(today):
    os.mkdir(today)
    print('Successfully created directory',today)

# 5.������zip����ļ������zip��ʽ
zip_command = 'zip -r {0} {1}'.format(target,' '.join(source))

# ���б���
print('Zip command is :')
print(zip_command)
print('Running:')
if os.system(zip_command) == 0:
    print('Successful backup to',target)
else:
    print('Backup Failed!')
```

> ͨ��`os.path.exists `������������ļ�Ŀ¼���Ƿ��Ѿ��������Ե�ǰ������Ϊ���Ƶ���Ŀ¼.�����δ���ڣ�����ͨ��` os.mkdir `����������һ��.


###    **������**

����ϣ���û���ѹ���ļ���ʱ��zip�ļ����Դ����û���˵��.

����Ϊ backup_ver3.py

```python

import os
import time

# 1.��Ҫ���ݵ��ļ���Ŀ¼����
# ָ����һ���б���
# ������windows��
# source = ['"C:\\My Documents"','c:\\Code']
# ����Mac OS X �� Linux�£�
# source = ['/users/swa/notes']
source = ['E:\\Coding\\es6study']
# ��������Ҫ���ַ�����ʹ��˫���ţ������������а����ո������

# 2.�����ļ�����洢��һ��������Ŀ¼��
# ������windows �£�
# target_dir = 'E:\\Backup'
# �������� Mac OS X �� Linux �£�
# target_dir = '/users/swa/backup'
target_dir = 'E:\\Testing'

# ���Ŀ��Ŀ¼�ļ���������Ҫ���д���
if not os.path.exists(target_dir):
    os.mkdir(target_dir)

# 3.�����ļ������ѹ����zip�ļ�
# 4.zipѹ���ļ����ɵ�ǰ������ʱ�乹��
today = target_dir+os.sep+time.strftime('%Y%m%d')
# ����ǰ��ʱ����Ϊzip�ļ����ļ���
now = time.strftime('%H%M%S')

# ���һ�������û�ע���Դ���
# zip �ļ����ļ���
comment = input('Enter a comment -->')
# ����Ƿ������ۼ���
if len(comment) == 0:
    target = today + os.sep+now+'.zip'
else:
    target = today + os.sep + now +'_'+\
             comment.replace(' ','_')+'.zip'


# �����Ŀ¼�в������򴴽�һ��
if not os.path.exists(today):
    os.mkdir(today)
    print('Successfully created directory',today)

# 5.������zip����ļ������zip��ʽ
zip_command = 'zip -r {0} {1}'.format(target,' '.join(source))

# ���б���
print('Zip command is :')
print(zip_command)
print('Running:')
if os.system(zip_command) == 0:
    print('Successful backup to',target)
else:
    print('Backup Failed!')
```

> ע�Ȿ��������Ϊ�û������޸�zip�ļ�����ʱҪע��ʹ��'\'��ע�����������к��߼��е�����


###    **�����Ľ�**

����ĳ����Ѿ��ܹ��Դ�����û���˵������������ع����Ľű���.���ǣ����ǲ��ܽ��������ڴˣ����ǻ�����ͨ�����`-v`��`-q`�ֱ�����ʾ��ʾ��ϸ��Ϣ���˳�����.
����Ҫ�ĸĽ��ǲ�ʹ��os.system�ķ����������鵵�ļ�������ʹ��zipfile����tarfile���õ�ģ�����������ǵĹ鵵�ļ�.���Ǳ�׼���һ���֣���ʱ�����ڵ�����û��zip�����ⲿ�����������������.


### **�������������**
*    what?
*    how?
*    do it!
*    test
*    use
*    maintain


---

#    **���������**

��֮ǰ���Ǳ�д�ĳ����ж���������̵�(Procedure-oriented)�ı�̷�ʽ�����ǽ���������Ҫѧϰһ�ָ�Ϊ�Ƚ���˼�뷽�����������.

�����������������̵�������Ҫ�ķ��档һ�����ܹ�����һ���µ����ͣ����ж��������ʵ��.

*    �ֶ�(Field): �����ڶ��������ı��������ֶ�
*    ����(Method): ������ĺ�����ʵ��ĳЩ����
> �ֶκͷ���ͳ��Ϊ�������(Attribute)

�ֶ�����������
*    ʵ������(Instance Variables)
*    �����(Class Variables)


###    **self**

�෽������ͨ����ֻ��һ���ض�������--ǰ�߱�����һ����������֣�������ֱ�����ӵ������б�Ŀ�ͷ�������㲻����������������ʱΪ���������ֵ.python ��Ϊ�����ض��ı��������Ƕ�����,��������`self`��һ����.

> python �е�self �൱��c++�е�ָ���java��c#�е�thisָ��


###    **��**

��򵥵���(class)����ͨ������İ�����չʾ(����Ϊoop_simplestclass.py)

```python
class Person:
    pass
    
p = Person()
print(p)
```

�����

![class.png](img/class.png "")


###    **����**

������

```python
class Person:
    def say_hi(self):
        print('Hello,how are you?')
        
p = Person()
p.say_hi()
# ͬ������д����Person().say_hi()

```

![method.png](img/method.png "")


###    **\_\_init\_\_ ����**

python���У��в��ٷ��������ƾ������������.��������Ҫ�˽�ľ���\_\_init\_\_����������.
\_\_init\_\_����������Ķ�����ʵ����ʱ��������.��һ�������Զ��κ�������в�����ľ��Ŷ������г�ʼ��(Initialization)

������

```python
class Person:
    def __init__(self,name):
        self.name = name

    def say_hi(self):
        print('Hello,my name is ',self.name)

p = Person('chenpeng')
p.say_hi()
# ͬ����Ҳ��������дPerson('Swaroop').say_hi()

```

������:

![init.png](img/init.png "")


> �ر�ע�����`self.name`�������name�Ķ�����self�����һ���֣���name����һ���ֲ�����.

###    **������Ͷ������**

�����Ѿ����۹����������Ĺ��ܲ��֣���������ѧϰ�鼮���֡�
�ֶ�ֻ���ǰ󶨵�������ֹ��������ռ�(Namespace).�ֶ�(Field)����������-������Ͷ������
*    �����(Class Variable)�ǹ���ģ����Ա�������������ʵ������.
*    �������(Object Variable)�����ÿһ�������Ķ����ʵ����ӵ��.ÿ������ӵ���������Լ��ֶεĸ�����Ҳ����˵���ǲ��ᱻ����.

������

```python
# coding=UTF-8

class Robot:
    """��ʾ��һ���������ֵĻ�����"""
    # һ����������������������˵�����
    population = 0

    def __init__(self,name):
        """��ʼ������"""
        self.name = name
        print("(Initializing({}))".format(self.name))

        # ���л����˱�����ʱ�������˻������˿ڵ�����
        Robot.population += 1

    def die(self):
        """�ҹ���"""
        print("{} is being destroyed!".format(self.name))

        Robot.population -= 1

        if Robot.population == 0:
            print("{} was the last one.".format(self.name))
        else:
            print("There are still {:d} robots working".format(Robot.population))

    def say_hi(self):
        """���Ի�������ϵ��ʺ�"""
        print('Gretting,my master call me {}.'.format(self.name))

    @classmethod
    def how_may(cls):
        """��ӡ��ǰ���˿�����"""
        print("we have {:d} robots.".format(cls.population))


droid1 = Robot("r2-D2")
droid1.say_hi()
Robot.how_may()

droid2 = Robot("C-3P0")
droid2.say_hi()
Robot.how_may()

print("\nRobots con do some work here.\n")

print("Robots have finished their work,So let's destory them")
droid1.die()
droid2.die()

Robot.how_may()
```

��������

![oop_obvar.png](img/oop_obvar.png "")

> `population`����`Robot`��,����һ�������.name ��������һ������,������һ���������
> ����ʹ��`Robot.population`�����ǻ�����ʹ��`self.__class__.population`����Ϊÿ������ͨ��`self.__class__`����������������.
>`how_many`ʵ������һ��������������ڶ���ķ����������ζ�����ǽ�������Ϊһ��`classmethod`���෽��������һ��`staticmethod(��̬����)`.
> ����ʹ��װ����(Decorator)����`how_many`�������Ϊ�෽��.
> `@classmethod`װ�����ȼ��ڵ���:`how_many = classmethod(how_many)
> ֻ��ʹ��self������ͬһ����ı����뷽�����ⱻ������������(Attribute Reference)
> ���ǻ�����ͨ��`Robot.__doc__`��������ĵ��ַ���,���ڷ����ַ�������ʹ��`Robot.say_hi.__doc__`
> ���е����Ա���ǹ����ģ�������pyton��������һ��Լ�������ʹ�����ݳ�Ա����������ʹ��˫�»�����Ϊǰ׺����`__privatevar`��������ʽ��python��ʹ�����Ƶ���(Name-mangling)��ʹ����Ч�س�Ϊһ��˽�б���.
> ���⣬���е����Ա(�������ݳ�Ա)���ǹ�����,����python�����еķ������������(Virtual)

###    **�̳�**

����:
```python
# coding=UTF-8

class SchoolMember:
    '''�����κ�ѧУ�����Ա'''

    def __init__(self,name,age):
        self.name = name
        self.age = age
        print('(Initialized schoolMember:{})'.format(self.name))

    def tell(self):
        '''�������й��ҵ�ϸ��'''
        print('Name:{},age:{}'.format(self.name,self.age))

class Teacher(SchoolMember):
    '''����һλ��ʦ'''

    def __init__(self,name,age,salary):
        SchoolMember.__init__(self,name,age)
        self.salary = salary
        print('(Initialized Teacher:{})'.format(self.name))

    def tell(self):
        SchoolMember.tell(self)
        print('Salray:{:d}'.format(self.salary))


class Student(SchoolMember):
    '''����һλѧ��'''
    def __init__(self,name,age,marks):
        SchoolMember.__init__(self,name,age)
        self.marks = marks
        print('(Initialized Student:{})'.format(self.name))

    def tell(self):
        SchoolMember.tell(self)
        print('Marks:{:d}'.format(self.marks))


t = Teacher('Mrs.Chen',24,6000)
s = Student('chenpeng',23,10000)

print()

members = [t,s]
for member in members:
    member.tell()

```
�����

![subclass.png](img/subclass.png "")







 
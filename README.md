***�ı�Ϊ��python���׽̡̳�����ѧ�ʼ�***

#    ��һ��

###    ʹ�ý�����ʾ��
��Python���������ʾ�����룺
            
```python
print("Hello World!");
```

���

![01.png](img/01.png "")

### ����˳���������ʾ��
>    GNU/LINUX ���� OS X�ϵ�shell����`ctrl+d' �������� `exit()`

>    WINDOWS: `ctrl+z [enter]` �˳�

### ʹ�ñ༭��

����ʹ����pycharm

![02.png](img/02.png "")


#    ����

### ע��
���ӣ�

        
```python
print('Hello world') # print is a function
```
        
### ���泣��

>    ���泣��������������23 4 ���������ֻ���`����һ���ı�` �������ı�

### ����

>    ������Ҫ������
>    *    ����(Integers)
>    *    ������(Floats)

### �ַ���

>�ַ���(string) ���ַ�(characters)������(sequence)
>    *    ������,����ʹ�õ�������ָ���ַ���,����˵`'���������������'`
>    *    ˫����,��˫���ź͵��������������ַ����乤��������һ����,����˵`"what's your name?`
>    *    ������,��������֮���ʵ�����Ƕ����ַ��������������������֮�����ɵ�ʹ�õ����ź�˫����        

### �ַ����ǲ��ɱ��

����ζ��һ���㴴����һ���ַ�������Ͳ��ܸı���

### ��ʽ������ 

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

###    ת������(Escape Sequence)

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
     
###    ԭʼ�ַ���

�������Ҫָ��һЩδ��������ַ���,����ת������,�������ַ���ǰ����`r`����`R`

```python
        r"Newlines are indicated by \n"
```
        
###    ����

ʹ���������޷��������ǿ��������� ��ʱ�����Ҫʹ�ñ���(veriables).

###    ��ʶ������

*    ��һ���ַ���������ĸ���е���ĸ(��СдASCII����Unicode����_)
*    ��ʶ�����������ֿ����ַ����»��ߡ��������
*    ��ʶ�����ִ�Сд

###    ��������

�������Խ�������ʽ��ֵ����Ϊ��ͬ����������,�������������Ͱ������ֺ��ַ������ں������ǽ�������ͨ����(Classes)�����������Լ�����������.

###    ����


��Ҫ��סpython���������κ�����ͳ��Ϊ����(Object).����һ������Ľз�������ͨ����ĳ����(object)��ƣ�����ĳ����(something)
 
###     ��α�дpython����

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

###    ���������߼���

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


### ����

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




#    ���������ʽ



��������д�Ĵ�������(�߼���)�������˱��ʽ(Expressions).
һ�����ʽ�ļ򵥵����Ӿ���`2+3`.���ʽ�����Բ��Ϊ
*    �����(Operators)
*    ������(Operands)

��`2+3`�����ı��ʽ�`+`�����������`2`��`3`���ǲ�����

###    �����

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
   

### ��ֵ�����븳ֵ�Ŀ�ݷ�ʽ

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

### ��ֵ˳��

�±�������python����������ȼ�

![yunsuan01.png](img/yunsuan01.png "")
![yunsuan02.png](img/yunsuan02.png "")

        
### �ı�����˳��

����ʹ��������ʹ�ñ��ʽ�����׶�

### �����

�����ͨ���������ҽ��

### ���ʽ

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


#    ������

python�������ֿ��������
*    if
*    for
*    while


### if���

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
![lh.png](img/lh.png "")
![lr.png](img/lr.png "")


> python �в�����switch���


### while ���

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

### for ѭ��

```python
for i in range(1,5):
    print(i)
else:
    print('The for loop is over')

```
����Ľ��Ϊ

![for.png](img/for.png "")

>���������������ʹ�������õ�`range`����������һ�������С�range(1,5)�������[1,2,3,4]�����������range�ṩ������������������ֽ���Ϊ����������range(1,5,2),�������[1,3],�ر�ע�ⲻ�����ڶ����������ڣ�������ѧ������������߿����䣬�ұ߱����䣬��������Ϊ������


### break ���


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


###  continue ���

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






 
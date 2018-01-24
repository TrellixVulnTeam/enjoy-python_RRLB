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

***\***����һ��������÷�������ĩβ��ʾ�ַ�������һ�м���:

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
        






 
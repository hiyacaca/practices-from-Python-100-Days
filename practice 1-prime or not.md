# practice1-prime or not
#练习1：输入一个正整数判断是不是素数。
#素数指的是只能被1和自身整除的大于1的整数。

a=int(input('输入一个正整数'))
if a==1:
    print('这不是素数')
else:
    for i in range(2,a):
        if a%i==0 or i==a:
            print('这不是素数')
            break
        else:
            continue
    else:
        print('这是素数')


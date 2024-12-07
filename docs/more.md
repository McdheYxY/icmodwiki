---
title: 更多
---
# 更多
| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

```python
#[18，20]=18×20÷（18，20）=18×20÷2=180

#最小公倍数=积/最大公约数

#最大公约数=辗转相除法

def zd(value1,value2):

    sy=divmod(value1,value2)

    if sy[1]==0:

        return value2

    if sy[0]==0:

        return zd(value2,value1)

    else:

        return zd(value2,sy[1])

def zx(value1,value2):

    ji=value1*value2

    zd1=zd(value1,value2)

    return ji/zd1

print(zx(18,20))
```

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]


[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
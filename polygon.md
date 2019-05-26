# Assignment
def polysum(n,s):
    import math
    pi=3.1415926
    x=pi/n
    area=0.25*n*s*s/(math.tan(x))


    return round(area,4)

print(polysum(4,5))

def polysum2(n,s):
    peri=n*s
    return peri
print(polysum2(4,5))

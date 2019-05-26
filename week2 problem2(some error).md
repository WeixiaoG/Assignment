# Assignment
bal=eval(input('bal'))
air=eval(input('air'))
mir=air/12
x=0
n=0
for i in range(12):
    while bal-x>0:
        mub=bal-x
        updated=mub+mir*mub
        bal=updated
        x+=10
print(x)



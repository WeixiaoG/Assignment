# Assignment
bal=eval(input('bal'))
ainterestr=eval(input('air'))
mpayrate=eval(input('mpr'))
minterestr=ainterestr/12

for i in range(12):
    minmpay=mpayrate*bal
    mub=bal-minmpay
    updated=mub+(minterestr*mub)
    bal=updated
print(round(bal,2))

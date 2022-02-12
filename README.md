ch=100
dch=180
ic=40
bsc=300
lolp=10
cname=input('enter customer name:')
Cphone=input('enter customer phn number:')
chq=int(input('enter no.of chocolates:'))
dchq=int(input('enter no.of dark chocolates:'))
icq=int(input('enter no.of ice creams:'))
bscq=int(input('enter no.of biscuit packets:'))
lolpq=int(input('enter no.of lolipops'))
bill=(ch*chq)+(dch*dchq)+(ic*icq)+(bsc*bscq)+(lolp*lolpq)
if bill>5000:
  disc=bill*10/100
  tax=bill*10/100
elif bill>3000:
    disc=bill*8/100
    tax=bill*10/100
elif bill>2000:
    disc=bill*5/100
    tax=bill*18/100
elif bill>1000:
    disc=bill*3/1000
    tax=bill*18/100
else:
    print('invalid')
mainbill=bill-disc+tax
print('bill amount:',mainbill)

OUTPUT:
enter no.of chocolates:5
enter no.of dark chocolates:8
enter no.of ice creams:4
enter no.of biscuit packets:3 
enter no.of lolipops10
bill amount: 3162.0

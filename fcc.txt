x = 5
if x == 5 :
    print("Equals 5")
if x > 4 :
    print('Greater than 4') 
if x >= 5 :
    print('greater than or equals 5')
if x < 6 : print('Less than 6')
if x <= 5 :
    print('less than or equals 5') 
if x != 6 :
    print('not equal to 6')
print(x)

x = 4
if x > 2 :
    print('bigger')
else :
    print('smaller')

print('all done')

if x < 2:
    print('small')
elif x < 10 :
    print('medium')
else :
    print('large')
print('all done')

sh = input('Enter Hours;')
sr = input('Enter Rate')
fh = float(sh)
fr = float(sr)
print(fh, fr)
xp = (fh * fr)
print("Pay:", xp)
  |№|статус|
  |1||
  |2||
  |3||
  |4||
  |5||
  |6||
  |7||
  |8||
  |9||
  |10||
|11||
|12||
|13||
|14||
|15||
|16||
|17||
|18||
|19||
|20||
|21||
|22||
|23||
|24||
|25||
|26||
|27||

print("|№|статус|")
for i in range(1,28):
  print(f"|{i}||")
  

b=f"{i:b}"
#b=bin(i)[2:]
i=10
print(b)
b="10"+b+"1"
c=int(b,2)
print(c)


черепаха
from turtle import *
left(90)
forward(220)
right(90)
forward(220)
right(135)
forward(320)
pu()
for x in range(0,15):
    for y in range(1,15):
        goto(x*15,y*15)
        dot(3)
done()

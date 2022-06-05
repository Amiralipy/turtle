
from turtle import *

bgcolor("lightgreen")#bgcolor==(b)ack(g)round color
color("red")#pencolor

for i in range(10):#shape is 10 sides
    
    for j in range(20,60,2):#From 20 to 60 2 to 2 Go ahead
        
        pensize(j)#Pen thickness as variable size j
        forward(5)
        
    penup()
    goto(0,0)#Table of coordinates of point (0,0)
    pendown()
    
    left(36)#360/10=>36(Because our shape is 10 sides)

color("orange") 
for i in range(10):
    
    for j in range(10,30):
        
        pensize(j)
        forward(3)
        
    penup()
    goto(0,0)
    pendown()
    
    left(36)

color("red") 
for i in range(10):
    
    for j in range(0,15):
        
        pensize(j)
        forward(2)
        
    penup()
    goto(0,0)
    pendown()
    
    left(36)
    
pensize(20)
color("olive")   
goto(0,0)
exitonclick()#When the program ends, hitting the mouse on the turtle window will program close






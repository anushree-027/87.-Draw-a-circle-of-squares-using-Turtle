# 87.-Draw-a-circle-of-squares-using-Turtle
import turtle
x = turtle.Turtle()

def square(angle):
    for _ in range(4):
        x.forward(100)
        x.right(angle)

for i in range(36):
    square(90)
    x.right(10)  # rotate to form a circle pattern

turtle.done()

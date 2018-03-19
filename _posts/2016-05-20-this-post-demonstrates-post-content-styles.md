---
layout: post
title: "Python Code"
---

import turtle

t = turtle.Turtle()

s = turtle.Turtle()
s.color("Blue")

def draw_a_polygon(a_turtle, number_of_sides):
  for loop_counter in range(number_of_sides):
    a_turtle.forward(100)
    a_turtle.right(360/number_of_sides)
    
# Draw a square
def draw_a_square(a_turtle):
  for loop_counter in range(4):
    a_turtle.forward(100)
    a_turtle.right(90)
  
# Draw a triangle
def draw_a_triangle():
  for i in range(3):
    t.forward(100)
    t.right(120)

draw_a_square(t)
s.goto(200,200)
draw_a_square(s)
draw_a_triangle()

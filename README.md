# Estrella-definitiva
En enlace a mi repositorio es el siguiente:https://github.com/blancabalmori/Estrella-definitiva.git

El código que he creado dibuja una estrella de n puntas:
import turtle
ws = turtle.Screen()
geekyTurtle = turtle.Turtle()
n = int (input ("inserte el número de puntas deseado: "))
for i in range (n):
    geekyTurtle.forward(100)
    geekyTurtle.right(360/n)
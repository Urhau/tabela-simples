# tabela-simples
from tkinter import Canvas
from tkinter import *


janela =Tk()
janela.title("Football Field")
janela.geometry("800x600")

# Colors

cor1 = "#0cba0b" # light green
cor2 = "078a06" # draw green
cor3 = "#ffffff" #white


# creating arccreate_line

canvasScreen = Canvas(janela, width= 700, height=500, bg=cor1)
canvasScreen.pack(pady = 80)
canvasScreen.create_line(350, 0, 350, 510, fill= "white")

canvasScreen.create_line(0, 350, 100, 350, fill= "white")
canvasScreen.create_line(0, 150, 100, 150, fill= "white")
canvasScreen.create_line(100, 350, 100, 150, fill= "white")

canvasScreen.create_line(800, 350, 600, 350, fill= "white")
canvasScreen.create_line(800, 150, 600, 150, fill= "white")
canvasScreen.create_line(600, 350, 600, 150, fill= "white")

canvasScreen.create_line(0, 185, 50, 185, fill= "white")
canvasScreen.create_line(0, 317, 50, 317, fill= "white")
canvasScreen.create_line(50, 185, 50, 317, fill= "white")

canvasScreen.create_line(700, 185, 650, 185, fill= "white")
canvasScreen.create_line(700, 317, 650, 317, fill= "white")
canvasScreen.create_line(650, 185, 650, 317, fill= "white")
canvasScreen.create_arc(500, 400, 400, 200, fill= "white")











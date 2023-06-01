# tabela simples
import pygame
from pygame.locals import *
from sys import exit

pygame.init()

largura = 700
altura = 500


tela = pygame.display.set_mode ((largura,altura))
pygame.display.set_caption('Campo de futebol')

while True:
    for event in pygame.event.get():
        if event.type == QUIT:
            pygame.quit()
            exit()
    pygame.draw.line(tela, (0,170,0), (500,0), (500,600),1000)

    pygame.draw.line(tela, (0,100,0), (100,0), (100,600),95)
    pygame.draw.line(tela, (0,100,0), (250,0), (250,600),95)
    pygame.draw.line(tela, (0,100,0), (450,0), (450,600),95)
    pygame.draw.line(tela, (0,100,0), (600,0), (600,600),95)

    pygame.draw.line(tela, (255,255,255), (350,0), (350,510),5)

    pygame.draw.line(tela, (255,255,255), (0,350), (100,350),5)
    pygame.draw.line(tela, (255,255,255), (0,150), (100,150),5)
    pygame.draw.line(tela, (255,255,255), (100,350), (100,150),5)

    pygame.draw.line(tela, (255,255,255), (800,350), (600,350),5)
    pygame.draw.line(tela, (255,255,255), (800,150), (600,150),5)
    pygame.draw.line(tela, (255,255,255), (600,350), (600,150),5)

    pygame.draw.line(tela, (255,255,255), (0,185), (50,185),5)
    pygame.draw.line(tela, (255,255,255), (0,317), (50,317),5)
    pygame.draw.line(tela, (255,255,255), (50,185), (50,317),5)

    pygame.draw.line(tela, (255,255,255), (700,185), (650,185),5)
    pygame.draw.line(tela, (255,255,255), (700,317), (650,317),5)
    pygame.draw.line(tela, (255,255,255), (650,185), (650,317),5)

    pygame.draw.circle(tela, (255,255,255), (350,250), 20)
    pygame.draw.circle(tela, (255,255,255), (70,250), 10)      
    pygame.draw.circle(tela, (255,255,255), (630,250), 10)

    pygame.draw.arc(tela, (255, 255, 255), (250, 150, 200, 200), 10, 20, 5) 

    pygame.draw.arc(tela, (255, 255, 255), (-40, -40, 80, 80), 10, 20, 5) #esquerdo cima

    pygame.draw.arc(tela, (255, 255, 255), (-40, 460, 80, 80), 10, 20, 5) # esquerdo baixo

    pygame.draw.arc(tela, (255, 255, 255), (665, 455, 80, 80), 10, 20, 5) #direito baixo

    pygame.draw.arc(tela, (255, 255, 255), (665, -40, 80, 80), 10, 20, 5) #direito cima

    

    

    
                                                 






    pygame.display.update()











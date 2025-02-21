#Importing required libraries.
import tkinter
import time
from tkinter import *
from tkinter import ttk
from tkinter import Label
from PIL import ImageTk, Image
import numpy as np
import random

#Initializing all the variables.
p1_image = None
p2_image = None

p1_label = None
p2_label = None

c1_button = ""
c2_button = ""
c3_button = ""
c4_button = ""

d1_button = ""
d2_button = ""
d3_button = ""
d4_button = ""

p1m1_cd = False
p1m2_cd = False
p2m1_cd = False
p2m2_cd = False

#When start is pressed, the code will transition to the character selection
#screen and place all the character buttons.
def start():
  global c1_button, c2_button, c3_button, c4_button

  start_button.place_forget()
  quit_button.place_forget()
  instr_button.place_forget()
  
  title = ImageTk.PhotoImage(Image.open("character_selection.png"))
  label.configure(image=title)
  label.image = title

  c1_button = tkinter.Button(window, text="P1 Choose", font=("Helvetica", 7)
                             , command=p1crc_1)
  c1_button.place(x=55, y=202)

  c2_button = tkinter.Button(window, text="P1 Choose", font=("Helvetica", 7)
                             , command=p1crc_2)
  c2_button.place(x=207, y=325)

  c3_button = tkinter.Button(window, text="P1 Choose", font=("Helvetica", 7)
                             , command=p1crc_3)
  c3_button.place(x=416, y=325)

  c4_button = tkinter.Button(window, text="P1 Choose", font=("Helvetica", 7)
                             , command=p1crc_4)
  c4_button.place(x=565, y=204)

  back_button.place(x=500, y=350)

#Defines the p1 character choice: appends the 1st character text file chosen
#by p1 to the player 1 array. The p1 choose buttons are then replaced by the
#p2 choose buttons.
def p1crc_1():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc
  charc = open("charc_1.txt", "r")
  p1charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p1charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()
  
  d1_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_1)
  d1_button.place(x=55, y=202)

  d2_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_2)
  d2_button.place(x=207, y=325)

  d3_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_3)
  d3_button.place(x=416, y=325)

  d4_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_4)
  d4_button.place(x=565, y=204)

  back2_button.place(x=500, y=350)

#Defines the p1 character choice: appends the 2nd character text file chosen
#by p1 to the player 1 array. The p1 choose buttons are then replaced by the
#p2 choose buttons.
def p1crc_2():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc
  charc = open("charc_2.txt", "r")
  p1charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p1charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()
  
  d1_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_1)
  d1_button.place(x=55, y=202)

  d2_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_2)
  d2_button.place(x=207, y=325)

  d3_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_3)
  d3_button.place(x=416, y=325)

  d4_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_4)
  d4_button.place(x=565, y=204)
  
  back2_button.place(x=500, y=350)

#Defines the p1 character choice: appends the 3rd character text file chosen
#by p1 to the player 1 array. The p1 choose buttons are then replaced by the
#p2 choose buttons.
def p1crc_3():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc
  charc = open("charc_3.txt", "r")
  p1charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p1charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()
  
  d1_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_1)
  d1_button.place(x=55, y=202)

  d2_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_2)
  d2_button.place(x=207, y=325)

  d3_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_3)
  d3_button.place(x=416, y=325)

  d4_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_4)
  d4_button.place(x=565, y=204)

  back2_button.place(x=500, y=350)

#Defines the p1 character choice: appends the 4th character text file chosen
#by p1 to the player 1 array. The p1 choose buttons are then replaced by the
#p2 choose buttons. 
def p1crc_4():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc
  charc = open("charc_4.txt", "r")
  p1charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p1charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()
  
  d1_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_1)
  d1_button.place(x=55, y=202)

  d2_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_2)
  d2_button.place(x=207, y=325)

  d3_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_3)
  d3_button.place(x=416, y=325)

  d4_button = tkinter.Button(window, text="P2 Choose", font=("Helvetica", 7)
                             , command=p2crc_4)
  d4_button.place(x=565, y=204)

  back2_button.place(x=500, y=350)

#Defines the p2 character choice: appends the 1st character text file chosen
#by p2 to the player 2 array. The background and buttons are then replaced
#with the battle background and the 2 chosen characters.
#The keybinds a,s and k,l, are also binded to perform the battle functions.
def p2crc_1():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc, p2charc
  global p1_image, p2_image
  global p1move_1, p1move_2, p2move_1, p2move_2
  global reset_p1m1_cd, reset_p1m2_cd, reset_p2m1_cd, reset_p2m2_cd
  global p1_health, p2_health, p1_health_val, p2_health_val
  global p1_label, p2_label, p1health_txt, p1health_txt2, p2health_txt
  global p2health_txt2
  charc = open("charc_1.txt", "r")
  p2charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p2charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()

  p1_health_val = p1_health()
  p2_health_val = p2_health()
  
  battle = ImageTk.PhotoImage(Image.open("battle.png"))
  label.configure(image=battle)
  label.image = battle
  
  p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))

  p1_label = Label(frame, image=p1_image)
  p1_label.place(x=30, y=80)

  p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))

  p2_label = Label(frame, image=p2_image)
  p2_label.place(x=510, y=80)
  
  d1_button.destroy()
  d2_button.destroy()
  d3_button.destroy()
  d4_button.destroy()

  c1_button.destroy()
  c2_button.destroy()
  c3_button.destroy()
  c4_button.destroy()

  back_button.place_forget()
  back2_button.place_forget()

  p1health_txt.configure(text=p2_health_val)
  p2health_txt.configure(text=p1_health_val)
  p1health_txt.place(x=567, y=50)
  p1health_txt2.place(x=600, y=50)
  p2health_txt.place(x=85, y=50)
  p2health_txt2.place(x=118, y=50)

  window.bind("<a>", p1move_1)
  window.bind("<s>", p1move_2)
  window.bind("<k>", p2move_1)
  window.bind("<l>", p2move_2)

#Defines the p2 character choice: appends the 2nd character text file chosen
#by p2 to the player 2 array. The background and buttons are then replaced
#with the battle background and the 2 chosen characters.
#The keybinds a,s and k,l, are also binded to perform the battle functions.
def p2crc_2():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc, p2charc
  global p1_image, p2_image
  global p1move_1, p1move_2, p2move_1, p2move_2
  global reset_p1m1_cd, reset_p1m2_cd, reset_p2m1_cd, reset_p2m2_cd
  global p1_health, p2_health, p1_health_val, p2_health_val
  global p1_label, p2_label, p1health_txt, p1health_txt2, p2health_txt
  global p2health_txt2
  charc = open("charc_2.txt", "r")
  p2charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p2charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()

  p1_health_val = p1_health()
  p2_health_val = p2_health()
  
  battle = ImageTk.PhotoImage(Image.open("battle.png"))
  label.configure(image=battle)
  label.image = battle
  
  p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))

  p1_label = Label(frame, image=p1_image)
  p1_label.place(x=30, y=80)

  p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))

  p2_label = Label(frame, image=p2_image)
  p2_label.place(x=510, y=80)

  d1_button.destroy()
  d2_button.destroy()
  d3_button.destroy()
  d4_button.destroy()

  c1_button.destroy()
  c2_button.destroy()
  c3_button.destroy()
  c4_button.destroy()

  back_button.place_forget()
  back2_button.place_forget()

  p1health_txt.configure(text=p2_health_val)
  p2health_txt.configure(text=p1_health_val)  
  p1health_txt.place(x=567, y=50)
  p1health_txt2.place(x=600, y=50)
  p2health_txt.place(x=85, y=50)
  p2health_txt2.place(x=118, y=50)
  
  window.bind("<a>", p1move_1)
  window.bind("<s>", p1move_2)
  window.bind("<k>", p2move_1)
  window.bind("<l>", p2move_2)

#Defines the p2 character choice: appends the 3rd character text file chosen
#by p2 to the player 2 array. The background and buttons are then replaced
#with the battle background and the 2 chosen characters.
#The keybinds a,s and k,l, are also binded to perform the battle functions.
def p2crc_3():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc, p2charc
  global p1_image, p2_image
  global p1move_1, p1move_2, p2move_1, p2move_2
  global reset_p1m1_cd, reset_p1m2_cd, reset_p2m1_cd, reset_p2m2_cd
  global p1_health, p2_health, p1_health_val, p2_health_val
  global p1_label, p2_label, p1health_txt, p1health_txt2, p2health_txt
  global p2health_txt2
  charc = open("charc_3.txt", "r")
  p2charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p2charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()

  p1_health_val = p1_health()
  p2_health_val = p2_health()
  
  battle = ImageTk.PhotoImage(Image.open("battle.png"))
  label.configure(image=battle)
  label.image = battle
  
  p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))

  p1_label = Label(frame, image=p1_image)
  p1_label.place(x=30, y=80)

  p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))

  p2_label = Label(frame, image=p2_image)
  p2_label.place(x=510, y=80)

  d1_button.destroy()
  d2_button.destroy()
  d3_button.destroy()
  d4_button.destroy()

  c1_button.destroy()
  c2_button.destroy()
  c3_button.destroy()
  c4_button.destroy()

  back_button.place_forget()
  back2_button.place_forget()

  p1health_txt.configure(text=p2_health_val)
  p2health_txt.configure(text=p1_health_val)  
  p1health_txt.place(x=567, y=50)
  p1health_txt2.place(x=600, y=50)
  p2health_txt.place(x=85, y=50)
  p2health_txt2.place(x=118, y=50)
  
  window.bind("<a>", p1move_1)
  window.bind("<s>", p1move_2)
  window.bind("<k>", p2move_1)
  window.bind("<l>", p2move_2)

#Defines the p2 character choice: appends the 4th character text file chosen
#by p2 to the player 2 array. The background and buttons are then replaced
#with the battle background and the 2 chosen characters.
#The keybinds a,s and k,l, are also binded to perform the battle functions.  
def p2crc_4():
  global back_button
  global back2_button
  global d1_button, d2_button, d3_button, d4_button
  global p1charc, p2charc
  global p1_image, p2_image
  global p1move_1, p1move_2, p2move_1, p2move_2
  global reset_p1m1_cd, reset_p1m2_cd, reset_p2m1_cd, reset_p2m2_cd
  global p1_health, p2_health, p1_health_val, p2_health_val
  global p1_label, p2_label, p1health_txt, p1health_txt2, p2health_txt
  global p2health_txt2
  charc = open("charc_4.txt", "r")
  p2charc = []
  info = charc.readline()
  info = info.strip()
  
  while (info != ""):
    p2charc.append(info)
    info = charc.readline()
    info = info.strip()
  charc.close()

  p1_health_val = p1_health()
  p2_health_val = p2_health()
  
  battle = ImageTk.PhotoImage(Image.open("battle.png"))
  label.configure(image=battle)
  label.image = battle
  
  p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))

  p1_label = Label(frame, image=p1_image)
  p1_label.place(x=30, y=80)

  p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))

  p2_label = Label(frame, image=p2_image)
  p2_label.place(x=510, y=80)

  d1_button.destroy()
  d2_button.destroy()
  d3_button.destroy()
  d4_button.destroy()

  c1_button.destroy()
  c2_button.destroy()
  c3_button.destroy()
  c4_button.destroy()

  back_button.place_forget()
  back2_button.place_forget()
  
  p1health_txt.configure(text=p2_health_val)
  p2health_txt.configure(text=p1_health_val)
  p1health_txt.place(x=567, y=50)
  p1health_txt2.place(x=600, y=50)
  p2health_txt.place(x=85, y=50)
  p2health_txt2.place(x=118, y=50)
  
  window.bind("<a>", p1move_1)
  window.bind("<s>", p1move_2)
  window.bind("<k>", p2move_1)
  window.bind("<l>", p2move_2)

#Initializing the functions to be used in the battle using the information
#from the character text files.
def p1_health():
  global p1charc
  p1_health = int (p1charc[2])
  return p1_health

def p2_health():
  global p2charc
  p2_health = int (p2charc[2])
  return p2_health

def p1_light():
  global p1charc
  p1_damage = 25 * (int (p1charc[3]))
  return p1_damage

def p1_heavy():
  global p1charc
  p1_damage = 50 * (int (p1charc[3]))
  return p1_damage

def p2_light():
  global p2charc
  p2_damage = 25 * (int (p2charc[3]))
  return p2_damage

def p2_heavy():
  global p2charc
  p2_damage = 50 * (int (p2charc[3]))
  return p2_damage

def p1_light_acc():
  global p1charc
  p1_light_acc = 1/(int(p1charc[3]))
  p1_light_acc = round((p1_light_acc), 2)
  return p1_light_acc
  
def p1_heavy_acc():
  global p1charc
  p1_heavy_acc = 1/(int(p1charc[3])) - 0.1
  p1_heavy_acc = round((p1_heavy_acc), 2)
  return p1_heavy_acc

def p2_light_acc():
  global p2charc
  p2_light_acc = 1/(int(p2charc[3]))
  p2_light_acc = round((p2_light_acc), 2)
  return p2_light_acc

def p2_heavy_acc():
  global p2charc
  p2_heavy_acc = 1/(int(p2charc[3])) - 0.1
  p2_heavy_acc = round((p2_heavy_acc), 2)
  return p2_heavy_acc

#Defining the "a" keypress, which is the p1 light attack.
#If the key is pressed and the move lands, it deals damage and displays Hit!
#text. Else, it misses and deals 0 damage, thus displaying miss text.
#Once the move is used, the cooldown text will be displayed below the
#character and will go away once the move is ready to be used again.
#If the light attack is used and the opponent's health goes to 0 or less
#than 0, a victory screen will be shown, crowning player 1 as the winner.
def p1move_1(event):
  global p1m1_cd
  global p1_light
  global p1_light_acc
  global p2_health
  global p1charc, p2charc
  global p1_image, p2_image
  global p1_label, p2_label
  global p2_health_val
  global p1m1cd_display, p1m2cd_display, p2m1cd_display, p2m2cd_display
  global p1m1_miss, p1m2_miss, p2m1_miss, p2m2_miss
  global p1m1_hit, p1m2_hit, p2m1_hit, p2m2_hit
  global p1health_txt, p1health_txt2, p2health_txt, p2health_txt2
  
  chance = random.uniform(0,1)
  chance = round(chance, 2)
  p2_health_val= p2_health()
  
  if (event.char == "a") and (p1m1_cd == False):
    accuracy = p1_light_acc()
    if (chance) <= (accuracy):
      p1_damage = p1_light()
      p2_health_val = p2_health_val - p1_damage

      p1health_txt.configure(text=p2_health_val)
      p1health_txt.place(x=567, y=50)
      p1health_txt2.place(x=600, y=50)
      
      p1m1_hit.place(x=420, y=130)
      window.after(1500, del_p1hit1)
    
    else:
      p1_damage = 0
      p2_health_val = p2_health_val - p1_damage
      p1m1_miss.place(x=420, y=130)
      window.after(1500, del_p1miss1)

    p2_health = lambda: p2_health_val
    
    if p2_health_val <= 0:

      p1_label.place_forget()
      p2_label.place_forget()
      
      win1 = ImageTk.PhotoImage(Image.open("p1_win.png"))
      label.configure(image=win1)
      label.image = win1

      p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))
      p1_label = Label(frame, image=p1_image)
      p1_label.place(x=280, y=170)

      p1health_txt.place_forget()
      p1health_txt2.place_forget()
      p2health_txt.place_forget()
      p2health_txt2.place_forget()
      p1m1cd_display.place_forget()
      p1m2cd_display.place_forget()
      p2m1cd_display.place_forget()
      p2m2cd_display.place_forget()

      window.unbind("<a>")
      window.unbind("<s>")
      window.unbind("<k>")
      window.unbind("<l>")

      quit_button.place(x=530, y=280)
        
    p1m1_cd = True
    p1m1cd_display.configure(text=p1charc[6])
    p1m1cd_display.place(x=32, y=305)
    window.after(4000, reset_p1m1_cd)

#These functions delete the hit and miss text after 1.5 secs. The cooldown
#text for the light attack is reset after 4 seconds.
def del_p1hit1():
  global p1m1_hit
  p1m1_hit.place_forget()  

def del_p1miss1():
  global p1m1_miss
  p1m1_miss.place_forget()  

def reset_p1m1_cd():
  global p1m1_cd, p1m1cd_display
  p1m1_cd = False
  p1m1cd_display.place_forget()

#Defining the "s" keypress, which is the p1 heavy attack. If the key is
#pressed and the move lands, it deals damage and displays Hit! text. Else,
#it misses and deals 0 damage, thus displaying miss text. Once the move is
#used, the cooldown text will be displayed below the character and will go
#away once the move is ready to be used again. If the heavy attack is used
#and the opponent's health goes to 0 or less than 0, a victory screen will
#be shown, crowning player 1 as the winner.
def p1move_2(event):
  global p1m2_cd
  global p1_heavy
  global p1_heavy_acc
  global p2_health
  global p1charc, p2charc
  global p1_image, p2_image
  global p1_label, p2_label
  global p2_health_val
  global p1m1cd_display, p1m2cd_display, p2m1cd_display, p2m2cd_display
  global p1m1_miss, p1m2_miss, p2m1_miss, p2m2_miss
  global p1m1_hit, p1m2_hit, p2m1_hit, p2m2_hit
  global p1health_txt, p1health_txt2, p2health_txt, p2health_txt2

  chance = random.uniform(0,1)
  chance = round(chance, 2)
  p2_health_val= p2_health()
  
  if (event.char == "s") and (p1m2_cd == False):
    accuracy = p1_heavy_acc()
    if (chance) <= (accuracy):
      p1_damage = p1_heavy()
      p2_health_val = p2_health_val - p1_damage

      p1health_txt.configure(text=p2_health_val)
      p1health_txt.place(x=567, y=50)
      p1health_txt2.place(x=600, y=50)
      
      p1m2_hit.place(x=420, y=210)
      window.after(1500, del_p1hit2)

    else:
      p1_damage = 0
      p2_health_val = p2_health_val - p1_damage
      p1m2_miss.place(x=420, y=210)
      window.after(1500, del_p1miss2)

    p2_health = lambda: p2_health_val

    if p2_health_val <= 0:
      
      p1_label.place_forget()
      p2_label.place_forget()

      win1 = ImageTk.PhotoImage(Image.open("p1_win.png"))
      label.configure(image=win1)
      label.image = win1

      p1_image = ImageTk.PhotoImage(Image.open(p1charc[1]))
      p1_label = Label(frame, image=p1_image)
      p1_label.place(x=280, y=170)

      p1health_txt.place_forget()
      p1health_txt2.place_forget()
      p2health_txt.place_forget()
      p2health_txt2.place_forget()
      p1m1cd_display.place_forget()
      p1m2cd_display.place_forget()
      p2m1cd_display.place_forget()
      p2m2cd_display.place_forget()

      window.unbind("<a>")
      window.unbind("<s>")
      window.unbind("<k>")
      window.unbind("<l>")

      quit_button.place(x=530, y=280)
    
    p1m2_cd = True
    p1m2cd_display.configure(text=p1charc[7])
    p1m2cd_display.place(x=32, y=345)
    window.after(7000, reset_p1m2_cd)  

#These functions delete the hit and miss text after 1.5 secs. The cooldown
#text for the heavy attack is reset after 7 seconds.
def del_p1hit2():
  global p1m2_hit
  p1m2_hit.place_forget()  

def del_p1miss2():
  global p1m2_miss
  p1m2_miss.place_forget()  

def reset_p1m2_cd():
  global p1m2_cd, p1m2cd_display
  p1m2_cd = False
  p1m2cd_display.place_forget()

#Defining the "k" keypress, which is the p2 light attack. If the key is
#pressed and the move lands, it deals damage and displays Hit! text. Else,
#it misses and deals 0 damage, thus displaying miss text. Once the move is
#used, the cooldown text will be displayed below the character and will go
#away once the move is ready to be used again. If the light attack is used
#and the opponent's health goes to 0 or less than 0, a victory screen will
#be shown, crowning player 2 as the winner.
def p2move_1(event):
  global p2m1_cd
  global p2_light
  global p2_light_acc
  global p1_health
  global p1charc, p2charc
  global p1_image, p2_image
  global p1_label, p2_label
  global p1_health_val
  global p1m1cd_display, p1m2cd_display, p2m1cd_display, p2m2cd_display
  global p1m1_miss, p1m2_miss, p2m1_miss, p2m2_miss
  global p1m1_hit, p1m2_hit, p2m1_hit, p2m2_hit
  global p1health_txt, p1health_txt2, p2health_txt, p2health_txt2
  
  chance = random.uniform(0,1)
  chance = round(chance, 2)
  p1_health_val= p1_health()

  if (event.char == "k") and (p2m1_cd == False):
    accuracy = p2_light_acc()
    if (chance) <= (accuracy):
      p2_damage = p2_light()
      p1_health_val = p1_health_val - p2_damage

      p2health_txt.configure(text=p1_health_val)
      p2health_txt.place(x=85, y=50)
      p2health_txt2.place(x=118, y=50)
      
      p2m1_hit.place(x=200, y=130)
      window.after(1500, del_p2hit1)

    else:
      p2_damage = 0
      p1_health_val = p1_health_val - p2_damage

      p2m1_miss.place(x=200, y=130)
      window.after(1500, del_p2miss1)
      
    p1_health = lambda: p1_health_val

    if p1_health_val <= 0:
      
      p1_label.place_forget()
      p2_label.place_forget()

      win2 = ImageTk.PhotoImage(Image.open("p2_win.png"))
      label.configure(image=win2)
      label.image=win2

      p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))
      p2_label = Label(frame, image=p2_image)
      p2_label.place(x=280, y=170)

      p1health_txt.place_forget()
      p1health_txt2.place_forget()
      p2health_txt.place_forget()
      p2health_txt2.place_forget()
      p1m1cd_display.place_forget()
      p1m2cd_display.place_forget()
      p2m1cd_display.place_forget()
      p2m2cd_display.place_forget()

      window.unbind("<a>")
      window.unbind("<s>")
      window.unbind("<k>")
      window.unbind("<l>")

      quit_button.place(x=530, y=280)    
    
    p2m1_cd = True
    p2m1cd_display.configure(text=p2charc[6])
    p2m1cd_display.place(x=507, y=305)
    window.after(4000, reset_p2m1_cd)

#These functions delete the hit and miss text after 1.5 secs. The cooldown
#text for the light attack is reset after 4 seconds.
def del_p2hit1():
  global p2m1_hit
  p2m1_hit.place_forget()  

def del_p2miss1():
  global p2m1_miss
  p2m1_miss.place_forget()  

def reset_p2m1_cd():
  global p2m1_cd, p2m1cd_display
  p2m1cd_display.place_forget()
  p2m1_cd = False

#Defining the "l" keypress, which is the p2 heavy attack. If the key is
#pressed and the move lands, it deals damage and displays Hit! text. Else,
#it misses and deals 0 damage, thus displaying miss text. Once the move is
#used, the cooldown text will be displayed below the character and will go
#away once the move is ready to be used again. If the heavy attack is used
#and the opponent's health goes to 0 or less than 0, a victory screen will
#be shown, crowning player 2 as the winner.
def p2move_2(event):
  global p2m2_cd
  global p2_heavy
  global p2_heavy_acc
  global p1_health
  global p1charc, p2charc
  global p1_image, p2_image
  global p1_label, p2_label
  global p1_health_val
  global p1m1cd_display, p1m2cd_display, p2m1cd_display, p2m2cd_display
  global p1m1_miss, p1m2_miss, p2m1_miss, p2m2_miss
  global p1m1_hit, p1m2_hit, p2m1_hit, p2m2_hit
  global p1health_txt, p1health_txt2, p2health_txt, p2health_txt2

  chance = random.uniform(0,1)
  chance = round(chance, 2)
  p1_health_val= p1_health()
  
  if (event.char == "l") and (p2m2_cd == False):
    accuracy = p2_heavy_acc()
    if (chance) <= (accuracy):
      p2_damage = p2_heavy()
      p1_health_val = p1_health_val - p2_damage

      p2health_txt.configure(text=p1_health_val)
      p2health_txt.place(x=85, y=50)
      p2health_txt2.place(x=118, y=50)
      
      p2m2_hit.place(x=200, y=210)
      window.after(1500, del_p2hit2)

    else:
      p2_damage = 0
      p1_health_val = p1_health_val - p2_damage

      p2m2_miss.place(x=200, y=210)
      window.after(1500, del_p2miss2)

    p1_health = lambda: p1_health_val

    if p1_health_val <= 0:

      p1_label.place_forget()
      p2_label.place_forget()

      win2 = ImageTk.PhotoImage(Image.open("p2_win.png"))
      label.configure(image=win2)
      label.image=win2

      p2_image = ImageTk.PhotoImage(Image.open(p2charc[1]))
      p2_label = Label(frame, image=p2_image)
      p2_label.place(x=280, y=170)

      p1health_txt.place_forget()
      p1health_txt2.place_forget()
      p2health_txt.place_forget()
      p2health_txt2.place_forget()
      p1m1cd_display.place_forget()
      p1m2cd_display.place_forget()
      p2m1cd_display.place_forget()
      p2m2cd_display.place_forget()
      
      window.unbind("<a>")
      window.unbind("<s>")
      window.unbind("<k>")
      window.unbind("<l>")

      quit_button.place(x=530, y=280)
    
    p2m2_cd = True
    p2m2cd_display.configure(text=p2charc[7])
    p2m2cd_display.place(x=507, y=345)
    window.after(7000, reset_p2m2_cd)

#These functions delete the hit and miss text after 1.5 secs. The cooldown
#text for the heavy attack is reset after 7 seconds.
def del_p2hit2():
  global p2m2_hit
  p2m2_hit.place_forget()  

def del_p2miss2():
  global p2m2_miss
  p2m2_miss.place_forget()  

def reset_p2m2_cd():
  global p2m2_cd, p2m2cd_display
  p2m2cd_display.place_forget()
  p2m2_cd = False

#Once the quit button is pressed at the end of the game, or if it is pressed
#at the beginning of the game, the game will transition to the quit screen
#background, and will close after 3.5 secs. Due to technical issues, there
#is an extra if else statement within the function. Essentially, if the user
#goes directly from the main menu to the quit screen via the quit button,
#there will be a None value for the p1 and p2 character images, which does
#not have the attribute .place. So, if that is the case, the if statement does
#not use that command, removes everything else from the screen, and replaces
#the background image. If they go to the quit screen via the quit button at
#the end of the game, then there will be a value for the p1 and p2 character
#images, which is when the else statement functions, removes the images, and
#then goes on to remove everything else from the screen and replace the
#background image.
def quit_game():
  global p1_label, p2_label

  if (p1_label == None):
    end_scrn = ImageTk.PhotoImage(Image.open("quit_scrn.png"))
    label.configure(image=end_scrn)
    label.image = end_scrn

    start_button.place_forget()
    quit_button.place_forget()
    instr_button.place_forget()

    window.after(3500, end_game)

  else:
    p1_label.place_forget()
    p2_label.place_forget()

    end_scrn = ImageTk.PhotoImage(Image.open("quit_scrn.png"))
    label.configure(image=end_scrn)
    label.image = end_scrn

    start_button.place_forget()
    quit_button.place_forget()
    instr_button.place_forget()
    
    window.after(3500, end_game)

def end_game():
  quit()

#This back button goes from the p1 character selection screen back to the
#main menu, then removesthe back button.
def back():
  global c1_button, c2_button, c3_button, c4_button
  im = ImageTk.PhotoImage(Image.open("pokeman2.png"))
  label.configure(image=im)
  label.image = im

  c1_button.destroy()
  c2_button.destroy()
  c3_button.destroy()
  c4_button.destroy()
  
  start_button.place(x=270, y=150)
  quit_button.place(x=270, y=240)
  instr_button.place(x=270, y=330)
  back_button.place_forget()

#This back buttons goes from the p2 character selection screen back to
#the p1 character selection screen, then replaces the back2 buttons with
#the back button.
def back2():
  global d1_button, d2_button, d3_button, d4_button
  title = ImageTk.PhotoImage(Image.open("character_selection.png"))
  label.configure(image=title)
  label.image = title

  d1_button.destroy()
  d2_button.destroy()
  d3_button.destroy()
  d4_button.destroy()

  c1_button.place(x=55, y=202)
  c2_button.place(x=207, y=325)
  c3_button.place(x=416, y=325)
  c4_button.place(x=565, y=204)
  back2_button.place_forget()

  back_button.place(x=500, y=350)

#This back button goes from the instructions page back to the main menu,
#then removes the back3 button.
def back3():
  im = ImageTk.PhotoImage(Image.open("pokeman2.png"))
  label.configure(image=im)
  label.image = im

  start_button.place(x=270, y=150)
  quit_button.place(x=270, y=240)
  instr_button.place(x=270, y=330)
  back3_button.place_forget()

#If the instructions button is pressed, it transitions to the instructions
#page by replacing all on screen elements and the background with the
#instructions page background. The back3 button is then placed on the screen
#so that the user can go back to the main menu.
def help_page():
  start_button.place_forget()
  quit_button.place_forget()
  instr_button.place_forget()

  help = ImageTk.PhotoImage(Image.open("instructions.png"))
  label.configure(image = help)
  label.image = help

  back3_button.place(x=145, y=325)

#This is the main menu code, which runs at the beginning of the game.
#This displays the main menu screen, with the start button, quit button,
#and instructions button.
window = Tk()
window.geometry("700x394")

frame = Frame(window, width=600, height=400, bg="white")
frame.pack()
frame.place()

im = ImageTk.PhotoImage(Image.open("pokeman2.png"))
label = Label(frame, image=im, width=900, height=600)
label.pack()

#This creates a style for the main buttons
style = ttk.Style()
style.configure('Custom.TButton', font=("Helvetica", 17), foreground="white"
                , background="#FF5733")

start_button = ttk.Button(window, text="Start", style='Custom.TButton'
                          , command=start)
start_button.place(x=270, y=150)

quit_button = ttk.Button(window, text="Quit", style='Custom.TButton'
                         , command=quit_game)
quit_button.place(x=270, y=240)

instr_button = ttk.Button(window, text="Instructions", style='Custom.TButton'
                          , command=help_page)
instr_button.place(x=270, y=330)

#All buttons are globally defined here so that they can be used and configured
#in all functions.
p1m1cd_display = ttk.Button(window, text="Cooldown")
p1m2cd_display = ttk.Button(window, text="Cooldown")
p2m1cd_display = ttk.Button(window, text="Cooldown")
p2m2cd_display = ttk.Button(window, text="Cooldown")

p1m1_miss = ttk.Button(window, text="Miss")
p1m2_miss = ttk.Button(window, text="Miss")
p2m1_miss = ttk.Button(window, text="Miss")
p2m2_miss = ttk.Button(window, text="Miss")

p1m1_hit = ttk.Button(window, text="Hit!")
p1m2_hit = ttk.Button(window, text="Hit!")
p2m1_hit = ttk.Button(window, text="Hit!")
p2m2_hit = ttk.Button(window, text="Hit!")

p1health_txt = ttk.Button(window, text="health", width = 3)
p1health_txt2 = ttk.Button(window, text="HP", width = 2)
p2health_txt = ttk.Button(window, text="health", width = 3)
p2health_txt2 = ttk.Button(window, text="HP", width = 2)

back_button = ttk.Button(window, text="Back", style='Custom.TButton'
                         , command=back)

back2_button = ttk.Button(window, text = "Back", style='Custom.TButton'
                          , command=back2)

back3_button = ttk.Button(window, text = "Back", style='Custom.TButton'
                          , command=back3)

window.mainloop()

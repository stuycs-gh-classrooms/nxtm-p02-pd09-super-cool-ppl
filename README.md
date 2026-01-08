[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pI6im86_)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22164319)
# NeXtCS Final Project
### Name 0: Avery Brosnick
### Name 1: Ruby Vaca 
---

### Project Description
Whack-a-mole. There will be regular and special "moles" that show up in random places in the window, and the player will have to click them within a certain time frame to earn points. Bombs will also show up randomly, and the player should avoid these. Each regular mole clicked will be +10 points, special are +30, and bombs are -20. After missing 5 moles or reaching -30 points, they're out. If they successfully whack 10 moles, they will get faster.

similar to this: https://wutools.com/fun/whac-a-mole

### Skill Usage
We will be using mouse control, random locations, shapes, classes, etc.

### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- space = pause
- r = reset

Mouse Control:
- Mouse movement: pointer moves with mouse.
- Mouse pressed: if on mole, points will increase; if not, lives will decrease. 


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

class Mole
- int xcor
- int ycor
- int size
- boolean pressed
- int countdown
- int type (reg, star, bomb)

class Pointer
- int size
- int lives
- int xcor
- int ycor

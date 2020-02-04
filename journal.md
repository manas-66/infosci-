# this is my journal for info science

1. what did we do?
we make a command for the robot to make him make a jelly sandwitch 
2. what did you learn?
- decomposition 
- pattern recognition
- abstraction
- algolithm
3. question i have

Today we worked on processing,

x = 0

def setup():

    size(1000,1000)
    
    background(255)
    
    textAlign(CENTER, CENTER)

def draw():
    print("")
    
def mouseClicked():
    x = mouseX
    
    y = mouseY
    
    r = random(10,100)
    
    myred = random(0,255)
    
    myblue = random(0,255)
    
    mygreen = random(0,255)
    
    fill (myred, mygreen, myblue)
    
    
    circle(x,y,r)
    
    fill (0)
    
    textSize(r/4);
    
    text("mana",x,y)
    
    print (x,y)
    
    
  ## homework secind class
  1. add lines from the middle of the window to each circle
  2. add lines from circle to circle

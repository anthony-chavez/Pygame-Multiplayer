# What is Pygame-Multiplayer?
This is a project where I re-created Pong in Python using the Pygame module. This version of Pong only supports multiplayer between 2 clients connecting to a local server. 

# Prerequisites
Latest version of Python 3!:

    To check if you have the right version of python3 run this command:
    
    python3 --version
    
    If you don't have it installed run this command:
    
    sudo apt-get install python3.6
    
Latest version of Pygame:
    
    To check if you have pygame installed run this:
    
    python3 -m pygame.examples.aliens
    
    If nothing runs then you need to download pygame using this command:
    
    python3 -m pip install -U pygame --user

# What are the controls?
There are two ways to controll your paddle:
    
    Up  : W or UP
    Down: D or Down
    
# How do I play?
First you will need to clone the repository on both computers that you plan on playing with.
Second you will start the server using this command:

    python3 server.py

Lastly run this command on the two computers you want to play on!:
    
    python3 client.py

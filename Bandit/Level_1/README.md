# Bandit Level 0 → Level 1
### Level Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.



    ~
    ➜ ssh bandit0@bandit.labs.overthewire.org -p 2220
    This is a OverTheWire game server. More information on http://www.overthewire.org/wargames
    bandit0@bandit.labs.overthewire.org's password:
    
    Welcome to OverTheWire!
    
    --[ More information ]--
    
    For more information regarding individual wargames, visit
    http://www.overthewire.org/wargames/
    
    For support, questions or comments, contact us through IRC on
    irc.overthewire.org #wargames.
    
    Enjoy your stay!
    
    bandit0@bandit:~$ ls
    readme
    bandit0@bandit:~$ cat readme
    boJ9jbbUNNfktd78OOpsqOltutMc3MY1
    bandit0@bandit:~$

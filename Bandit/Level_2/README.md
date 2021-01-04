# Bandit Level 1 → Level 2
### Level Goal
The password for the next level is stored in a file called - located in the home directory



    ~
    ➜ ssh bandit1@bandit.labs.overthewire.org -p 2220
    This is a OverTheWire game server. More information on http://www.overthewire.org/wargames
    bandit0@bandit.labs.overthewire.org's password:
    
    Welcome to OverTheWire!
    
    --[ More information ]--
    
    For more information regarding individual wargames, visit
    http://www.overthewire.org/wargames/
    
    For support, questions or comments, contact us through IRC on
    irc.overthewire.org #wargames.
    
    Enjoy your stay!
    
    bandit1@bandit:~$ ls -larth
    total 24K
    -rw-r--r--  1 root    root     675 May 15  2017 .profile
    -rw-r--r--  1 root    root    3.5K May 15  2017 .bashrc
    -rw-r--r--  1 root    root     220 May 15  2017 .bash_logout
    drwxr-xr-x  2 root    root    4.0K May  7  2020 .
    -rw-r-----  1 bandit2 bandit1   33 May  7  2020 -
    drwxr-xr-x 41 root    root    4.0K May  7  2020 ..
    bandit1@bandit:~$ cat ~/-
    CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
    bandit1@bandit:~$

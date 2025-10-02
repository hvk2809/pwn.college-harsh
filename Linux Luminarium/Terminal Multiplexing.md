# Terminal Multiplexing
## Launching Screen
- Process: write the command screen
- Flag: pwn.college{wFv0cl_odMS69C2LO2bio0QtNKS.QX1gjM4EDLzUjN0czW}
## Detaching and Attacking
- Process: First launch screen and then detach it using the command Ctrl-a and then d. After detaching give command /challenge/run and then retach it using screen -r to get the flag
- Flag: pwn.college{4QT0NZS8lo8JshummhcCHkeA17S.QX2gjM4EDLzUjN0czW}
## Finding Sessions
- Process: Go through all the screens in screen -l and detach it if the flag is not present, in the last screen flag will be found.
- Flag: pwn.college{8oQmDLwkAnaMvk_eg4oEODAFiNY.QX3gjM4EDLzUjN0czW}
## Switching Windows
- Process: Retach to the screen and switch to 0 window to find the flag
- Flag: pwn.college{U_RDLLfDutfoHiI_k84uH9mY8EY.QX4gjM4EDLzUjN0czW}
## Detaching and Attaching
- Process: Enter the command tmux to launch a seesion after that detach it by entering Ctrl-b followed by d after that run /challenge/run and after that again retach it using tmux a
- Flag: pwn.college{UD_wEHoQbJnEsEO8HBg1vvvE3C7.QX5gjM4EDLzUjN0czW}
## Swtiching Windows(tmux)
- Process: Retach the tmux and then switch window using Ctrl-b followed by 0
- Flag: Here is your flag: pwn.college{wSjn1r-BND0LQcUA_HgSRgwQDNQ.QXwkjM4EDLzUjN0czW}

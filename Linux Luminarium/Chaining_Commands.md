# Chaining Commands
## Chaining with Semicolons
- Process: Enter the first command followed by ; and then the second command which will execute both the commands
- Flag: pwn.college{Urb9ZutqDxFCErwPDhQ5g1_txkm.dVTN4QDLzUjN0czW}
## Building on Success
- Process: chain the command /challenge/first-success and /challenge/second using &&
- Flag: pwn.college{8UuOu60e2kyr9ws-tVCfanjRAB8.QXyQzM4EDLzUjN0czW}
## Handaling Faliure
- Process: Chain the command /challenge/first-failure and /challenge/second using || so that if first one fails then second one will run
- Flag: pwn.college{kZ5htfwjFCYgiDItejmldkzgtuR.QXzQzM4EDLzUjN0czW}
## Your First Shell Script
- Process: Using nano write the commands in x.sh file and then pass the x.sh file as argument to bash
- Flag: pwn.college{siXiekX-QHSvRaM3k19-MHiiKX2.dFzN4QDLzUjN0czW}
## Redirecting Script Output
- Process: create a .sh file with commands /challenge/pwn and /challenge/college and then pipe the output to /challenge/solve
- Flag: pwn.college{g8uW-EJG0qFuL-45CnE9NC8pbhb.dhTM5QDLzUjN0czW}
## Executable Shell Scripts
- Process: Create a .sh file with command /challenge/solve and then make the .sh file executable using chmod command and then execute it.
- Flag: pwn.college{QuFVqbDQXY05hMnhYutqsCxO6dG.dRzNyUDLzUjN0czW}
## Understaing Shebangs
- Process: Write a shebang script to print "hack the planet" and then run /challenge/run
- Flag: pwn.college{Ugk0hsYk5D_sUBEpxyxPMfyLifC.QX5MzM4EDLzUjN0czW}
## Scripting with Arguments
- Process: In the shelbang script write "echo "$2 and $1"" and save it and then run /challenge/run
- Flag: pwn.college{wsoIk3V5Wzj8A8Rrxfq57r7xZGY.QX1MzM4EDLzUjN0czW}
## Scrpting with Conditionals
- Process: Write a shellbang script with the condition to change pwn to college and then run /challenge/run
- Flag: pwn.college{kOcUCB1zBxL4n9kMTsjE8VYGLUq.QX2MzM4EDLzUjN0czW}

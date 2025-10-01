# File Globbing
## Match with *
- Process: pass the argument /ch* to cd which change the directory to /challenge and then execute /challenge/run
- Flag: pwn.college{IyJZfbu6zTucv9Gp-qVC92rH6Mf.dFjM4QDLzUjN0czW}
## Matching with ?
- Process: pass the argument /?ha??enge to cd and then execute /challenge/run
- Flag: pwn.college{AvbSOUENqp31FmWQjNVoUnzeRl8.dJjM4QDLzUjN0czW}
## Matching with []
- Process: change directory to /challenge/files and then execute /challenge/run file_[bash]
- Flag: pwn.college{cgeA55SSRfdENWxxRp-xn7PyPvs.dNjM4QDLzUjN0czW}
## Matching path with []
- Process: execute /challenge/run followed by absolute path of files
- Flag: pwn.college{0WHyiCWQw5oVOUw1N7aw3u1wF95.dRjM4QDLzUjN0czW}
## Multiple Globs
- Process: Change directory to /challenge/files using cd and give argument *p* to /challenge/run
- Flag: pwn.college{41XRqT4FYRO7OPnlWPHTWHdVYQq.QXycTO2EDLzUjN0czW}
## Mixing Globs
- Process: execute the line [cep]*
- Flag: pwn.college{wtgMUaM9o43aPY1rhDrQBGS3OqP.dVjM4QDLzUjN0czW}
## Exclusionary Globbing
- Process: Execute the line /challenge/run [!pwn]*
- Flag: pwn.college{k8TJhRLwoFx0jR0bBtu3GQB38eA.dZjM4QDLzUjN0czW}
## Tab Completion
- Process: Used tab complete, after writing the command /challenge/pwn<tab> it auto filed it and after enter flag was revealed
- Flag: pwn.college{gw-z3A6-Dtxk5W-kd2m1IfPthaw.QX0QTM3EDLzUjN0czW}
## Multiple options for tab Completion
- Process: cat all the files in /challenge/files until file is found. It was found in pwncollege-flag
- Flag: pwn.college{AIh9DoBKXTBq9uNmc_5vDmiEaBj.QX2QTM3EDLzUjN0czW}
## Tab Completetion on Commands
- Process: cat all the files in /challenge/files until file is found. It was found in pwncollege-flag
- Flag: pwn.college{AIh9DoBKXTBq9uNmc_5vDmiEaBj.QX2QTM3EDLzUjN0czW}

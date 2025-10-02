# Practicing Piping
## Redirecting Output
- Process: echo output PWN to file COLLEGE
- Flag: pwn.college{kcNZXB_c4sVMj13klNx5e8SVWiy.dRjN1QDLzUjN0czW}
## Redirecting more Output
- Process: /challenge/run > myflag and then cat myflag
- Flag: pwn.college{0sxCEAU4-AUgaka3RBmlN4ahh4P.dVjN1QDLzUjN0czW}
## Appending Output
- Process: Two times append /challenge/run to my-flag
- Flag: pwn.college{4YpWsv5FJYST4QVnrGYcHfZWVKI.ddDM5QDLzUjN0czW}
## Redirecting Errors
- Process: Redirect Errors to instructions and output to myflag and then cat myflag
- Flag: pwn.college{0bakp9Gs0LbNYkX7nYwyCZRjfhS.ddjN1QDLzUjN0czW}
## Redirecting Input
- Process: First echo the word College to PWN and then redirect it to /challenge/run
- Flag: pwn.college{Irc2Hv_F3jpK4xtzUYdWkMJDWF8.dBzN1QDLzUjN0czW}
## Grepping Stored Results
- Process: First direct the output of /challenge/run to tmp/data.txt and then grep the word pwn
- Flag: pwn.college{wZ8tBi77YTtzEYXLJj2ACN1dJhN.dhTM4QDLzUjN0czW}
## Greping Live Output
- Process: execute /challenge/run and grep pwn using pipe(|)
- Flag: pwn.college{Q3bFiD-yBOpy3U4qi79XZdAFswR.dlTM4QDLzUjN0czW}
## Greping Errors
- Process: first redirect standard error to standard output using 2>&1 and then grep pwn
- Flag: pwn.college{AmAkRzGzb8Ke1fJRBpkj-v8-vsr.dVDM5QDLzUjN0czW}
## Filtering with grep -v
- Process: pipe the command /challenge/run to grep -v DECOY to find all the lines which do not have the word DECOY
- Flag: pwn.college{Y-12tiQp0SeeptOrr3ObUwMBL_k.QX4ETM3EDLzUjN0czW}
## Duplicating Piped Data with Tee
- Process: tee the copy of pwn to different file and then cat the file to get secret code and then execute both the command
- Flag: pwn.college{80y2Y8lMCa-F-PVY53PYHZeGiQ3.dFjM5QDLzUjN0czW}
## Process Subsitution for Input
- Process: Use diff command and process subsitution to to achieve the goal
- Flag: pwn.college{8UC3_uAOWpU5h0toMqHhLsG4yFh.QX2AzM4EDLzUjN0czW}
## Writing to Multiple Commands
- Process: Duplicate the data to give input in two files using tee >()
- Flag: pwn.college{8KKzRGazMR6KGQTQxXxsZqUMyGo.dBDO0UDLzUjN0czW}
## Split-piping stderr and stdout
- Process: Send stderr to /challenge/the and stdout to /challenge/planet from /challenge/hack
- Flag: pwn.college{sfq9jbovLejTbSdOx8PxHU2Ykq-.dFDNwYDLzUjN0czW}
## Named Pipes
- Process: First create a FIFO using mkfifo and then open it as a reader using cat after that redirect /challenge/run to the created fifo
- Flag: pwn.college{UXNxnXopcWtayHXWHBfN9fobUEq.QXzMzM4EDLzUjN0czW}


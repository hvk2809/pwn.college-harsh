# Data Manipulation
## Translating Characters
- Process: change all the cases using tr command
- Flag: pwn.college{0I_pE7_lAUjxLNj3BysAnqPEwwC.QXzETM3EDLzUjN0czW}
## Deleting Characters
- Process: delete ^ % characters using tr -d
- Flag: pwn.college{k6XaD-BeRFrabkSxfFFKQRqwcHs.QX0ETM3EDLzUjN0czW}
## Deleting Newlines
- Process: delete newline using tr- -d
- Flag: pwn.college{0PSunEoOB5fsZKFTc2yRhLyuQ6R.QX1ETM3EDLzUjN0czW}
## Extracting the First Line with Head
- Process: Pipe /challenge/pwn to head -n to extract first seven lines and then pipe that to /challenge/college
- Flag: pwn.college{ErOTgIHmJfWATatzrNdjJz2LeR9.QX2ETM3EDLzUjN0czW}
## Extracting specific sections of text
- Process: Pipe /challenge/run to cut where use -d to cut through spaces and then select second column which again pipe it to remove new lines using tr
- Flag: pwn.college{cgtNnBaCA1QqHuvHseK3_Sqzl3U.QX3ETM3EDLzUjN0czW}
## Sorting Data
- Process: Sort the file and the last flag is the actual flag
- Flag: pwn.college{UHPuk3MiC27HAHa8CcSG2AxR9DM.QXwQzM4EDLzUjN0czW}


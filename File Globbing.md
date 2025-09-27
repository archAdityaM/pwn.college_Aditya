# Matching with *

### use globbing to enter the directory /challenge

**Flag:** `pwn.college{QEeoh7X8Ww7DRN0jQx6Mjh0erX6.QXxIDO0wyN5kjNzEzW}`

used cd /ch* which made me enter the directory /challenge
then used /challenge/run to get the flag

## What I learned
We can easily search or open files with the help of their staritng letters this might help us in scenarios where we are looking for files starting with a particular word or letter.

## References

pwn.college




# Matching with ?

### using ? 

**Flag:** `pwn.college{Q_9onPJeMDv58QyehYhI1DN3wnO.QXyIDO0wyN5kjNzEzW}`

used cd /?ha??enge to open the directory then /challenge/run to get the flag

## What I learned

We can use commands with arguments where we forgot a few letters of the file or in scenarios where only one letter is different in the files we have to search and we can list them out like filea fileb filec

## References

pwn.college




# Matching with []

### using []

**Flag:** `pwn.college{cbhaN0nt1wu35Sqc17-VDFjp_oC.QXzIDO0wyN5kjNzEzW}`

cd /challenge/files
/challenge/run file_[absh]

## What I learned
 If we know the letters we have to look for in place of ? we can put those letters in [] and it will show results accordingly

## References

pwn.college



# Matching paths with []

### using []

**Flag:** `pwn.college{Qy6sHY4QkSlnfVCDDhYjbtJLuhr.QX0IDO0wyN5kjNzEzW}`

used cd to go through directories and find the directory containing files
then cd to /home/hacker
then /challenge/run /challenge/files/file_[absh]

## What I learned
I can use [ ] in an argument that is an absolute path

## References

pwn.college



# Multiple Globs

### using multiple globs

**Flag:** ` pwn.college{Qy6sHY4QkSlnfVCDDhYjbtJLuhr.QX0IDO0wyN5kjNzEzW}`

went to the directory with cd
then /challenge/run *p*

## What I learned
we can use globbing even if we know a part of the word in the middle or start or end.

## References
pwn.college



# Mixing globs

### using all types of globbing at once

**Flag:** `pwn.college{Mx0vOEy9uFMvPTaj0HcoOxgzngA.QX1IDO0wyN5kjNzEzW}`

```
cd /challenge/files
/challenge/run [cep]*
```



## What I learned
 using ls

## References

chat gpt




# Exclusionary Globbing

### usinr ^ and ! with []

**Flag:** `pwn.college{oAnDIArGUh35Bau_1tKh0Tzxrax.QX2IDO0wyN5kjNzEzW}`

cd into the directory /challenge/files
/challenge/run [^pwn]* to get the flag



## What I learned
I can put letters I need to exclude from my search

## References

pwn.college



# Tab completion

### using tab to autocomplete

**Flag:** `pwn.college{IhTowUJM3Gss8wg-s8AwTieQG6d.0FN0EzNxwyN5kjNzEzW}`

cd /challenge
cat pw(press TAB) which autocompletes to cat pwncollege and gives the flag

## What I learned
 using tab to autocomplete 

## References

pwncollege




# Multiple Options for tab completion

### use tab completion

**Flag:** `pwn.college{UaF-pz5errmg-kWEea-LK0clI_r.0lN0EzNxwyN5kjNzEzW}`

cd into the mentioned directory , press tab two times to see all the files starting from p , then cat the file name with flag in it



## What I learned
 using tab completion

## References

chat gpt




# Tab completion on commands

### use tab completion for commands

**Flag:** `pwn.college{8IJRIqPcV0dPB_YXQjqSqDpUVXX.0VN0EzNxwyN5kjNzEzW}`

used tab after typing pwncollege to auto complete the command then got the flag

## What I learned
we can use tab completion for commands as well

## References

chat gpt






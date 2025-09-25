# Cat not the pet but the command

### use cat to find flag

**Flag:** `pwn.college{w44Kn5iMcgXwruQlaXd64i_3Nn4.QXxcTN0wyN5kjNzEzW}`

used the command cat with argument flag to read the contents of flag

```
cat flag
```

## What I learned

We use cat to read the contents of a text file .

## References

chat gpt




# Catting absolute paths

### use cat to find flag

**Flag:** `pwn.college{cvQxZsrq5fq1OR6tHL_d8l8tZPk.QX5ETO0wyN5kjNzEzW}`

used the command cat with argument /flag to read the contents of flag

```
cat /flag
```

## What I learned

We use cat to read the contents of a text file . we can also use it with absolute path

## References

chat gpt




# more catting practice

### use cat to find flag

**Flag:** `pwn.college{YWM0x7Qh22lgcfFkhFwR0vp2oPd.QXwITO0wyN5kjNzEzW}`

used the command cat with argument absolute path to read the contents of flag

```
cat /usr/share/gst-plugins-base/flag
```

## What I learned
 using cat with absolute path

## References

chat gpt



# Grepping for a needle in a haystack

### finding something particular in a text file using grep command

**Flag:** `pwn.college{E-EmtwOjJRn_E4XqVJQalGr_HV_.QX3EDO0wyN5kjNzEzW}`

used the command grep with argument /challenge/data.txt and pwn.college to find the flag

```
grep pwn.college /challenge/data.txt 
```

## What I learned
 using grep to find particular data in large amount of data

## References

chat gpt



# Comparing files

### use diff to find flag

**Flag:** ` pwn.college{UEGarZtRkGgHRDyvnX6_MEe_oOH.01MwMDOxwyN5kjNzEzW}`

used the command diff with absolute path of both the files which gave the flag

```
cat /usr/share/gst-plugins-base/flag
```

## What I learned
 using diff we can pinpoint where and what are different between two files

hacker@dojo:~$ cat file1
hello
world
hacker@dojo:~$ cat file2
hello
universe
hacker@dojo:~$ diff file1 file2
2c2
< world
---
> universe
The output tells us that line 2 changed (2c2), with world in the first file (<) being replaced by universe in the second file (>).

hacker@dojo:~$ cat old
pwn
hacker@dojo:~$ cat new
pwn
college
hacker@dojo:~$ diff old new
1a2
> college
This tells us that after line 1 in the first file, the second file has an additional line (1a2 means "after line 1 of file1, add line 2 of file2").


## References

chat gpt



# Listing files

### use ls

**Flag:** `pwn.college{EFw0Mqi-JL5WNMwqp8dCB2p36m5.QX4IDO0wyN5kjNzEzW}`

used the command ls to see the files in the current directory



## What I learned
 using ls

## References

chat gpt




# touching files

### use touch to create files

**Flag:** `pwn.college{UdNDY7DGJUkBtU6U67mhVuNf2K2.QXwMDO0wyN5kjNzEzW}`

used the command touch to create a file and get the flag



## What I learned
we can create files with touch

## References

chat gpt


# removing files

### use rm to remove file

**Flag:** `pwn.college{8fEwSbyOW9qR2-nXTuYyGYeuAAF.QX2kDM1wyN5kjNzEzW}`

used the command rm to remove file to get the flag
=

## What I learned
 we can use rm to remove file 

## References

chat gpt




# moving files

### use mv to move files

**Flag:** `pwn.college{Mvd7DnwHYaZDMp7tyrhoPXu7C_D.0VOxEzNxwyN5kjNzEzW}`

used the command mv to move file from source to destination.



## What I learned
 using mv

## References

chat gpt




# hidden files

### use ls -a 

**Flag:** `pwn.college{kWMFQshAcEPkDXVvS0QIFpOi4bN.QXwUDO0wyN5kjNzEzW}`

went to root directory using cd / , used ls -a , found the flag file , used cat .flag-139962443021517

```
cd /
ls -a
cat .flag-139962443021517

```

## What I learned
files starting with . cannot be seen with ls , they require ls -a to be seen

## References

chat gpt




# making directories

### make directory using mkdir

**Flag:** `pwn.college{gVMN3H3herffSaKFPtZCdt5Vt3q.QXxMDO0wyN5kjNzEzW`

make a directory using mkdir and a file using touch to get the flag


## What I learned
 using mkdir

## References

chat gpt





# Finding Files

### use find to find the flag

**Flag:** `pwn.college{YUubnu4NQVqW4EDrX6URTM3r3Hs.QXyMDO0wyN5kjNzEzW}`

used find / -name flag
openened all the directories named flag with cd
one of them showed not a directory then I opened a directory above flag , found the flag there



## What I learned
 using find

## References

chat gpt





# An Epic File System Quest

### use cat and cd to find flag

**Flag:** `pwn.college{UPeNZlkoSpzNey3dBGqDtPY5hZs.QX5IDO0wyN5kjNzEzW}`

used cat and cd to find flag
used ls with absolute path to check file name without cd
then directly used cat with absolute path



## What I learned
 using cat and cd

## References

chat gpt




# Linking files

### use ln -s

**Flag:** `pwn.college{oZ8_ynif67nAcxFBlHJw1JuKDT4.QX5ETN1wyN5kjNzEzW}`

Create a symbolic link from /home/hacker/not-the-flag to /flag
Run the challenge program



## What I learned
 using ln -s

## References

chat gpt


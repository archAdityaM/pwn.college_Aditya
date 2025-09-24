# The Root

### Invoke a program through its absolute path

**Flag:** `pwn.college{Y_pvKKmrx6252hPK2hcNQokn3HO.QX4cTO0wyN5kjNzEzW}`

I put the path of the file which was /pwn in the terminal and it gave me the flag


```
/pwn
```



## What I learned

Files are stored in directories , and these directories are stored in other directories , all such directoried are stored in the root directory which is represented by / . In linux we have /usr for all the system files , /usr/bin for all the executable programs /usr/lib for all the libraries used by the programs and much more directories . this path is known as the absolute path. 

## References

https://youtu.be/b67Jq6IZ3U8?list=PL-ymxv0nOtqqRAz1x90vxNbhmSkeYxHVC




# Program and Absolute Paths

### Allows us to execute a program that is inside another directory inside the root directory.

**Flag:** `pwn.college{4cc8OY3d4usZ1qs4q5Yj8wJ7reU.QX1QTN0wyN5kjNzEzW}`

I put the absolute path ( /challenge/run ) of the program run in the terminal and it gave me the flag
```
/challenge/run
```

## What I learned

I learnt how to open files that are inside directories inside the root directory

## References
only the pwn college 





# Position Thyself

### Teaches us to navigate through directories.

**Flag:** `pwn.college{8pu8oHDRKe5iuWdE9INT-2hzEWh.QX2QTN0wyN5kjNzEzW}`

I first used /challenge/run this told me that the path is in /tmp . Then I used cd /tmp to navigate to the tmp directory , there I used /challange/run which gave me the flag
```
/challenge/run
cd /tmp
/challenge/run
```

## What I learned

We can navigate into directories through cd , also we need to be in a directory to be able to run programs through absolute path into the directory. Also we can use pwd to get the current location where we are.

## References

only the pwn college site



# Position Elsewhere 

### Teaches us to navigate through directories.

**Flag:** `pwn.college{A7M-wQL2Y3FO4XzlHi7oGPJnjyq.QX3QTN0wyN5kjNzEzW}`

Same as above . I first used /challenge/run this told me that the path is in /tmp . Then I used cd /tmp to navigate to the tmp directory , there I used /challange/run which gave me the flag

```
/challenge/run
cd /tmp
/challenge/run
```

## What I learned

We can navigate into directories through cd , also we need to be in a directory to be able to run programs through absolute path into the directory. Also we can use pwd to get the current location where we are.

## References

only the pwn college site




# Position Yet elsewhere 

### Teaches us to navigate through directories.

**Flag:** `pwn.college{A7M-wQL2Y3FO4XzlHi7oGPJnjyq.QX3QTN0wyN5kjNzEzW}`

Same as above . I first used /challenge/run this told me that the path is in /home . Then I used cd /home to navigate to the home directory , there I used /challange/run which gave me the flag

```
/challenge/run
cd /home
/challenge/run
```

## What I learned

We can navigate into directories through cd , also we need to be in a directory to be able to run programs through absolute path into the directory. Also we can use pwd to get the current location where we are.

## References

only the pwn college site




# Implicit Relative Path from /

### Teaches us about relative path

**Flag:** `pwn.college{s95ZKuf_moFbw8Yg52eVe3DWnEo.QX5QTN0wyN5kjNzEzW}`

I navigated to the root directory , there I used challenge/run to get the flag.



## What I learned

we can use relative path if we are in the directory , ie , we were in the root directory so we could simpl write challenge/run

## References

only the pwn college site




# Explicit Relative Path from /

### Teaches us about relative path

**Flag:** `pwn.college{o6tInaGxJLOrHTyvNkRpzx_2muF.QXwUTN0wyN5kjNzEzW}`

I navigated to the root directory , there I used ./challenge/run to get the flag.

```
cd /
./challenge/run

```


## What I learned

Every directory has two special entries . and ..
. means current directory so adding it doesnt affect anything
.. means parent directory

/challenge
/challenge/.
./challenge
./././challenge

all are same
The starting ./ means "start from the current directory, then "

Adding more ./ doesn't change anything it's still the same path.

naked relative path


## References

chat gpt




# Implicit Relative Path 

### Teaches us about relative path

**Flag:** `pwn.college{wgRc1aPNKFprfGElkaJ5pXbErxp.QXxUTN0wyN5kjNzEzW}`

I navigated to the root directory , there I went to /challenge , from there I used ./run to get the flag.
```
cd /
cd /challenge
./run
```


## What I learned
If we simply put run it might execute another program with the same name so we have to mention we mean the program in the current directory only


## References

only the pwn college site



# Home Sweet Home

### Teaches us about relative path

**Flag:** `pwn.college{IBpKg2cayqiMk_4v4epvMR1EaOc.QXzMDO0wyN5kjNzEzW}`

I wrote challenge/run ~/a to get the flag , this copied the flag into a in /home/hacker .

```
/challenge/run ~/a
```

## What I learned

1. Your Home Directory

You are the user hacker.

Your personal folder (home directory) is: /home/hacker
That's where you can create and save your own files.

2. The ~ Shortcut

The tilde (~) is just a shortcut for your home directory.

cd ~ : goes to /home/hacker

~/something : means /home/hacker/something

## References

chat gpt


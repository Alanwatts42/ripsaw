# RIPSAW

--- 

<br>

## Why? Because it's METAL!!

At any rate, I find it useful. Basically it's a bash script that you can 
run inside a directory to unzip or unarchive multiple zipped (archived) 
files. It can handle multiple archive formats: .zip, .7z, .rar, tar, tar.bz, tar.gz, and even .ecm.

<br>

## Can I use it on my terrible computer?

It's a bash script, and I can only say for certain that it works on 
the OS for which it was written, Linux. It is possible that it might run 
on Microsoft's Linux sub-system software that lets you run a somewhat cut-
down version of a variety of Linux builds inside Windows 10. It is 
possible that it might run on Mac OS X (though I haven't tested it yet.) 

## How am I supposed to actually use this?

Since ripsaw happens to be without a GUI at the moment, it must be run 
rom the terminal. You can either:

### Method 1 (dumb method)

    - Run it by typing the full path leading to the 'ripsaw' file into the terminal and pressing 'enter' to execute it. )

### Method 2 (smart method)

    1. `sudo chmod +x ripsaw` - this makes ripsaw executable, just do it.
    2. `sudo cp ripsaw /usr/bin/ripsaw` - copies ripsaw from the current directory to the directory where the user's bash commands are kept which is `/usr/bin/`. I'm assuming here that ripsaw is in the current working directory a.k.a. the folder that you 're in right now, so keep that in mind when you're following these instructions.
    3. If you've done steps 1 and 2 correctly, all you should need to do to execute ripsaw now is to type `ripsaw` into the terminal and press `enter`. 
    4. Remember, before you execute ripsaw, you'll want to make sure you've used `cd` to change to the directory that you want to use ripsaw in, for example: `cd ~/Downloads` would navigate you to the Downloads directory so that when you execute `ripsaw` it will proceed to slice and dice all of the archives in your Downloads directory, but that's it, have fun nerds.

<br>

## Do it yourself, ya bums!

Be aware that in rare cases, one of the utilities that ripsaw uses to 
unarchive these files will want you to press a key to decide whether to 
overwrite a file, or something similar. I haven't bothered to find a way 
around this yet, mostly because I'm lazy, but also becuase I'd rather 
leave that up to the individual to decide what they want to do each time 
this comes up, that way no one can blame me if something gets
overwritten. If you want to blame me, I suppose I can't stop you, but it 
won't bring back your overwritten files.

<br>

## You fools! You were so concerned with whether or not you could, you never stopped to think about whether or not you should!

I wrote this script because I was sick to death of running a bunch of
seperate and repetitive commands to "unrar", "unzip", or "unecm" things,
and then remember to "rm" the original archive without accidentally
deleting what I just unarchived. This just automates the process.

<br>

## Dependencies and what not

That said, this obviously means that in order for ripsaw to work, you'd 
need to install each of these unarchiving tools before ripsaw would be 
able use them to unarchive that particular filetype.

Here is a list of those pre-requisite command line utilities:

    - bash (or other equivalent linux shell, zsh will work for example)
    - unrar
    - ecm-uncompress
    - unzip
    - 7z

<br>

## What? What do you want?

If you have any suggestions, especially if there's a file format that can 
be unarchived that ripsaw can't already rip into, go ahead and let me 
know using git's infrastructure (however that works), or via email at 
evan.sherwood@keemail.me.

Enjoy, nerds.

















### You can't sue me, nor should you, nor will I ever show up to court if you do.

And remember, I am in no way responsible for anything you do with this 
script, nor will I be held responsible for anything you thought this 
script could do if in fact, it turns out that it doesn't do whatever it 
is you thought it was going to do. If you try to come after me about 
anything at all, whatsoever, related to this, or anything I've put up on 
github, you will be sorely out of luck, because I have hereby declared 
forthrightly that I am in no way, shape, or form, responsible or liable 
for any sort of warantee, promise, gaurantee, or any synonym of any of 
those words, which you inferred or thought was implied on anything I have 
uploaded, becuase no such promise or gaurantee, has ever or will ever 
exist on anything I have uploaded to this website. I make no claims, no 
promises, and no affirmative statements of any kind, and any that you 
choose to interpret from anything I've written or uploaded will be a 
figment of your own imagination, and will not be upheld nor fulfilled in 
any way by myself or anyone who may come to be associated with me in any 
way. You are on your own, I will not support anything I put up here, and 
if you choose to use it and it screws you somehow, that's on you, and I 
will not be held responsible for any damages you incur, ever.

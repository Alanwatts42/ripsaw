# RIPSAW

--- 

<br>

## Why? Because it's METAL!!

At any rate, I find it useful. Basically it's a bash script that you can 
run inside a directory to unzip or unarchive multiple zipped (archived) 
files. It can handle multiple archive formats: .zip, .7z, .rar, and .ecm. 
The only reason I called it ripsaw is that "rip" sounds like "zip", and 
"saw" implies motorized or rapid motion, and because it sounds cool, does 
it not?

<br>

## How do I use it?

Right now, it will probably only work on a Linux OS or Microsoft's recent
Linux-within-Windows software that lets you run a somewhat cut-down 
version of multiple Linux builds inside an instance of Windows 10. Having 
used it myself, it's not bad for some purposes, though I was never able 
to get it to run anything with a GUI, and therefore just did everything 
through the terminal. 

Ripsaw does happen to be a terminal-only tool, so it will happily run on 
your abomination of a Windows 10 machine if you install the Linux sub-
system. 

You can either just run the Ripsaw script by typing out the full path to 
it and executing it as you would with any other script, or for extra 
credit, first make ripsaw executable using `sudo chmod + x ./ripsaw` and 
then make it a permanent command by placing it in /usr/bin/ with `sudo 
cp /usr/bin/ripsaw`. After you've done that, you can just `cd` into any 
directory you want, but probably your Downloads folder, and then just 
type `ripsaw` and press enter to run it. Then just sit back, and watch it 
open up all of those archives. 

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


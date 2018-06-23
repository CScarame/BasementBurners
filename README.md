# Basement Burners Records

## Introduction

This is the Basement Burners Library.  Anything you need to know about the Burners, you can find here.  Over time this place will fill with records of the world, and of the people who inhabit it.  For now it's a bit empty, but that's okay.  First of all, I'm sure you're wondering how to use this library.  There's some complicated magic in place to make sure no one tampers with the library without permission.

## Access

EDIT:  Message me on Discord.  We can figure it out together!

To access the library, you need to summon Git to your computer.  First you will need to make an account here, which hopefully you have already done.  I will help you do some computer magic now.  Follow the instructions for your operating system,.

### Windows

You can download it [here](https://git-scm.com/downloads).  Once you do, allow it to run.  Press next a bunch until you get to the page titled "Adjusting your PATH environment".  Choose the top option here.  It says "Use Git for Git Bash only".  Click it!!!  Next through everything else, and hopefully it will all work and you can click Install.  Now there should be a new program installed in your computer called GitBash.  Open it up.  It should open a window that's almost all black on the inside. Type in the following command word for word.

    ssh-keygen -t rsa -b 4096 -C "YOUREMAIL@nd.edu"
    
Ok.  You just made an RSA encryption key for your computer.  You need to use this to validate your github account. Now you are going to go to your File Explorer and go to **C:**, then click on **Users**, then click on *your username*, then click on **.ssh**.  If you don't see **.ssh**, then got to the __**View**__ tab at the top of your explorer and check the box that says "Hidden Items".  From here, you should see a file that says id_rsa.pub.  Right click on that and say "Open with...".  You'll get a window opening that asks what you want to use to open it.  Click more apps, Then scroll until you find notepad.  THen open it up in Notepad.  Copy the entire contents of the file to your clipboard.  

Ok you're doing great.  You currently have the public decryption key to your very own RSA encryption copied to your clipboard.  Now go to the settings page of your GitHub account(look in the top right corner of this page).  On the left hand side select **SSH and GPG keys**.  Select the green button that says **New SSH key**.  Paste your code into the big box(make sure you delete your e-mail from the end of it if it's there, then put any cool sounding name for your computer into the small box above it and confirm.  You just set up a secure RSA connection between your computer and your GitHub account.  Wooo!

### Apple

Honestly just do what the Windows one says, but however you Mac weirdos do it.  Link is [here](https://git-scm.com/downloads).

### Both

Ok.  you're almost done.  I just realized this is way more complicated than I want it to be.  Maybe no on this?  Hmmmm.  Anyway.  You're gonna have to open up GitBash again.  Then say

git clone git@github.com:CScarame/BasementBurners.git

that should hopefully work.  Now whenever you need to save changes, just open up git bash and say 

git pull
 
git commit

You'll have to confirm your commits, then say

git push

Ok I think thats it!
Woo.  God this is so complicated to explain here.  Just message me.  We can share screens and figure it out as a team.

## Contents

### Character Sheets

Post all of your Character Sheets in this folder.  We can keep them updated and rollback to see the old versions of them.  (WOW version control is so cool!!!)

### Intel

Post any information about possible jobs/quests/missions etc here, and I will too

### Lore

Post any interesting theories or information about the world here.

### Resources

The PHB and blank character sheets can be found here.

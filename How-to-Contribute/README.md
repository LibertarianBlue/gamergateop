How to Contribute to the GitGud
=======================================================================

This guide is still in development, please post feedback [over on its issue page](http://gitgud.net/gamergate/gamergateop/issues/6)!

## Contents

1. [Make an account](#how-to-quickly-make-an-account)
2. [Using the Web Editor](#web-editor)
3. [Setup SSH keys](#ssh-keys)
4. [Fork and make changes to your repository](#fork-the-repository)
5. [Merge your changes](#merge-your-changes)
6. [Keep your repository updated](#how-to-update-your-copy)
7. [Open issues and contribute to existing issues](#open-issues-and-contribute-to-existing-issues)

![Image: Iwantyou](http://a.pomf.se/usysfm.jpg)

### [\[⇧\]](#contents) How to quickly make an account

Go to [gitgud.net](http://gitgud.net/users/sign_in) and [sign up](http://gitgud.net/users/sign_up).  
Try to use an email address you'll be able to check for updates with. For example [cock.li](http://cock.li/register.php) is one such provider.


### [\[⇧\]](#contents) Web Editor

#### First, fork the repostory

![Image: Step1](http://a.pomf.se/wcndqs.png)

#### Next, select Files

![Image: step2](http://a.pomf.se/rlhmva.png)

#### Click the file you want to change then press edit

![Image: step3](http://a.pomf.se/cvymsh.png)

#### Make your changes then write a short description of what you did, then save it with commit

![Image: step4](http://a.pomf.se/znweiy.png)

#### Once done, click merge requests

![Image: step5](http://a.pomf.se/tueilg.png)

#### Select new merge requests

![Image: step6](http://a.pomf.se/vexkvo.png)

#### Then click master from the drop down (or whichever branch you made changes on) and then click compare branches and submit your merge for review.

![Image: step7](http://a.pomf.se/vjdlnb.png)


## [\[⇧\]](#contents) Advanced

If you don't want to use the web editor and are comfortable with git see below!  
If you're unfamiliar with git, [check out this tutorial](http://git-scm.com/book/en/Getting-Started-Git-Basics)!

### [\[⇧\]](#contents) SSH Keys

If you've never used ssh or something similar to gitgud before, you'll need to setup your ssh keys. Not to worry, it's a very quick process!  
Our old friends GitLab and GitHub have made guides for this:
- GitLab: [Youtube Video](https://www.youtube.com/watch?v=54mxyLo3Mqk), the instructions are exactly the same on GitGud.
- GitHub: [Text Guide](https://help.github.com/articles/generating-ssh-keys/), ignore the last part about testing it out.

### [\[⇧\]](#contents) Fork the repository

![Image: forking](http://a.pomf.se/cilxve.png)

In the top right of the [GamerGate Repository](http://gitgud.net/gamergate/gamergateop) 
you'll see a fork button, click that to make your own copy of the repository
on your account. You can then use git to pull down your repository over HTTP
and make your changes.

You'll also want to setup an _upstream_ remote pointing to this one by running
the following command:

    git remote add upstream http://gitgud.net/gamergate/gamergateop.git

then you can get the latest by running 

    git pull upstream master

at any time. 


### [\[⇧\]](#contents) Merge Requests

Once you've worked on something, you'll want to [make a merge request](http://gitgud.net/gamergate/gamergateop/merge_requests)
to the master branch of the main repository. You can assign it to any of the
people who have access to the repository and the pull request will be reviewed.

**Please do not be discouraged if we ask you to change something**, we try
very hard to keep the information in the repo up to date and factually
accurate. Also, if any requests imply harassment or any of the other 
bullshit the mainstream media tries to paint us with, we'll ask for it
to be changed. While we **all** know \#GamerGate is not about that, we
can still try to nip any potential complaints in the bud.


### [\[⇧\]](#contents) How to Update your copy

You'll want to keep the latest and most up to date information on your
repository, this means pulling and merging the code from the main repository
into your own local and remote versions. This is as easy as adding the 
remote [(see above)](#fork-the-repository) and then running

    git pull upstream master

### [\[⇧\]](#contents) Open issues and contribute to existing issues

You can check out the [open issues here](http://gitgud.net/gamergate/gamergateop/issues)
if you see one you think you can take on, please do! Many improvements to the
repository can be done by anyone, such as crossing out sponsors who have 
withdrawn support, updating news links, adding archive links and more. All
you really need to know how to do is write some markdown, and even if you 
don't, an examination of the source code of the repository will help inform
you how to write it. 

Even if you can't write in markdown and just want to contribute plain txt, we
can always take it and make it shiny later. Information and knowledge don't
need to be pretty to be accepted, it just has to be factual.

If you don't want to go through all this trouble you can still talk to us
in irc on Rizon in the \#4free channel! Or reach out to us on [twitter!](http://twitter.com/gitgudgg)

![Image: salute](http://a.pomf.se/spkxaj.jpg)

[Gater salute and I want you source](https://twitter.com/G4M3RG8R/status/522619436486758400)
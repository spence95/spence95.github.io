---
layout: post
title:  "Setting up a Private Git"
date:   2016-01-08
categories: how to
---
We've been programming this capstone project for a while now on public Github. While Github is a great service, there's just some things you shouldn't
have up for everyone to see. Since we're making a mobile app, we're gonna have private keys related to publishing the app later. We can't have everyone
knowing that! I hear that's a common problem, people accidentally pushing their private keys to public Github. We are hosting the git repo on a linux machine.
We're connecting to it with windows machines.

I thought this would be a straightforward process and for the most part it was. Here's the steps I had to take:

* We created public and private SSH keys
* I made sure that key worked by logging into the server through Putty
* On the server, we made an empty folder and did 'git init --bare' <- 'bare' means it's a repo we can push to
* On my local computer, I created a blank folder and did 'git init' in that folder
* I converted my private key to an OpenSSH key with PuttyGen
* I added that key to C:/Users/spence95/.ssh/ on my local machine (I had to create a .ssh folder)
* I renamed that key to id_rsa (wut) <- This was a difficult step to figure out for some reason
* We gave my user on the server permissions to the git repo with chmod
* I did 'git clone /path/to/git/repo/.git' on my local machine
* I did 'git remote add /path/to/git/repo/.git' on my local machine
* I copied in my files from the old repo into that same folder
* I did 'git add *'
* I did 'git commit -m "initial commit"'
* I did 'git push /path/to/git/repo/.git'

And that did it. The hardest parts to figure out were naming the key id_rsa and converting it to an OpenSSH key

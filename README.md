chopen-workshop-git
===================

Git workshop for ch/open 2013

Setup
===================

This workshop does not require a lot of tooling in place. No need for build tools, IDEs and stuff.

As we will be juggling with Git quite a bit during hands-on lab we strongly recommend sandboxed environment, so you won't do any harm to your daily system of choice.
We are also planning to practice some shell kung-fu therefore some Linux distrubtion might be a good choice.


You can use [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [this Ubuntu image](sourceforge.net/projects/imagesvm/files/linux/ubuntu/12.04/2/lts/desktop/x64/) (if possible, assign at least 1 GB of RAM).

We have prepared shell commands for Ubuntu distribution to get you started quickly. Just execute following in the shell (ctrl+alt+t):

```
sudo add-apt-repository -y ppa:pdoes/ppa
sudo apt-get update
sudo apt-get install -y curl tree meld git git-svn git-flow git-cola python-inotify
curl -o ~/.git-prompt.sh https://raw.github.com/git/git/master/contrib/completion/git-prompt.sh
curl https://raw.github.com/ctpconsulting/chopen-workshop-git/master/git-shell >> .bashrc
. ~/.bashrc
```

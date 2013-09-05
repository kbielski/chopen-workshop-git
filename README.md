chopen-workshop-git
===================

Git workshop prepared for [ch/open 2013](http://www.ch-open.ch/wstage/workshop-tage/2013/aktuelles-programm-2013/).


Setup
===================

This workshop does not require a lot of tooling in place. No need for build tools, IDEs and stuff.

As we will be juggling with Git quite a bit during hands-on lab we strongly recommend sandboxed environment, so you won't do any harm to your daily system of choice.
We are also planning to practice some shell kung-fu therefore some Linux distrubtion might be a good choice.

We strongly recommend that you use [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [VM prepared by ch/open team](http://data.workshoptage.ch/images/ws16/)  (or [this Ubuntu image](http://sourceforge.net/projects/imagesvm/files/linux/ubuntu/12.04/2/lts/desktop/x64/) alternatively). If possible, assign at least 1 GB of RAM.

We have prepared shell commands for Ubuntu distribution to get you started quickly. Just execute following in the shell (CTRL+ALT+T):

```
sudo add-apt-repository -y ppa:pdoes/ppa
sudo apt-get update
sudo apt-get install -y curl tree meld git git-svn git-flow git-cola python-pyinotify
curl -o ~/.git-prompt.sh https://raw.github.com/git/git/master/contrib/completion/git-prompt.sh
curl https://raw.github.com/ctpconsulting/chopen-workshop-git/master/git-shell >> .bashrc
. ~/.bashrc
```

Or you can simply run following one liner

```
{ wget https://raw.github.com/ctpconsulting/chopen-workshop-git/master/install.sh -O install.sh; chmod u+x install.sh; ./install.sh; }
```

If you don't want to use Ubuntu please let us know upfront (foss@ctp.com) so we can give you advices for other environments. We can't guarantee however that all labs will be working smoothly, as we are going to test it only on the suggested environment.

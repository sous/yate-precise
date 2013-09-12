== Yate Precise Build

This is a build of Yate 4.3.0 for Ubuntu Precise Pangolin 12.04

This is an apt repository. However, you cannot reference it directly hosted on github.

You must clone locally and refer to it directly:

    git clone https://github.com/sous/yate-precise
    ( echo deb file://`pwd`/yate-precise precise main
      echo deb-src file://`pwd`/yate-precise precise main ) > /etc/apt/sources.list.d/yate-precise.list

The gpg key for this repo can be imported using:

    curl https://raw.github.com/sous/yate-precise/master/apt-key.gpg | sudo apt-key add -


# xsbts

## What's this?

A quite easy way to launch several versions of sbt. 

## Setup

```sh
mkdir -p ~/bin

cd ~/bin
git clone git://github.com/seratch/xsbts.git

if [ ! `grep 'PATH=${PATH}:${HOME}/bin/xsbts' ${HOME}/.bash_profile` ]; then
  echo "PATH=\${PATH}:\${HOME}/bin/xsbts" >> ${HOME}/.bash_profile
fi

source ~/.bash_profile
```


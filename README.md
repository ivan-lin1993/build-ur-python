# Build Ur Own Python version

Source: <a herf='https://www.python.org/ftp/python/'>https://www.python.org/ftp/python/</a>

## Why need to build your own python?
Do you know how MANY python version on your mac or your linux?\
Just build your Own fav python version and stop using apt, yum and brew

```
sudo apt update
sudo apt install -y build-essential libpng-dev
sudo apt install -y libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev

curl -LO https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tgz
tar -xvzf Python-3.6.5.tgz
cd ./Python-3.6.5 
./configure 
make
sudo make install
# sudo make altinstall
# make altinstall is used to prevent replacing the default python binary file /usr/bin/python
```

## Uninstall
You can do :

1. make clean removes any intermediate or output files from your source / build tree
1. If you can, running make uninstall will work.
1. The last option is you have to manually uninstall it. Running make -n install

Note : You must cd the file location where you make install

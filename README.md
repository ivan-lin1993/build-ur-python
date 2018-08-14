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
```


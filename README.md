# Build Ur Own Python version

Source: <a herf='https://www.python.org/ftp/python/'>https://www.python.org/ftp/python/</a>
```
sudo apt update
sudo apt install -y build-essential libpng-dev
sudo apt install -y libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev

curl -LO https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tgz
cd ./Python-3.6.5 
./configure 
make
sudo make install
```


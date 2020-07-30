# Install BeerSmith-2 on Ubuntu 20.04

```
sudo add-apt-repository 'deb http://archive.ubuntu.com/ubuntu bionic main universe'
sudo add-apt-repository ppa:linuxuprising/libpng12
sudo apt update
sudo apt install libpng12-0
sudo apt install -t bionic libwebkitgtk-1.0-0 libjavascriptcoregtk-1.0-0
sudo apt install -f
sudo dpkg -i BeerSmith-2.3.12_amd64.deb
```


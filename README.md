# repo

## Installation

### Install

```sh
wget -qO - https://raw.githubusercontent.com/ReqBaa/repo/master/PUBLIC.KEY | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/reqbaa.key >/dev/null
echo "deb [signed-by=/etc/apt/trusted.gpg.d/reqbaa.key] https://raw.githubusercontent.com/ReqBaa/repo/master/ bionic main" | sudo tee /etc/apt/sources.list.d/reqbaa.list >/dev/null
sudo apt-get update
sudo apt-get install reqnotes
```

### Remove

```sh
sudo apt-get remove reqnotes
```





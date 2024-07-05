                     ▄█████   ▒█████    ███▄ ▄███▓  ▒█████    ███▄    █ 
                     ██▒ ▀█▒ ▒██▒  ██▒ ▓██▒▀█▀ ██▒▒ ██▒  ██▒  ██ ▀█   █ 
                    ▒██░▄▄▄░ ▒██░  ██▒ ▓██    ▓██░▒ ██░  ██▒ ▓██  ▀█ ██▒
                    ░▓█  ██▓ ▒██   ██░ ▒██    ▒██ ▒ ██   ██░ ▓██▒  ▐▌██▒
                    ░▒▓███▀▒░ ████▓▒░  ▒██▒   ░██▒░  ████▓▒░ ▒██░   ▓██░
                     ░▒   ▒ ░ ▒░▒░▒░ ░ ▒░   ░  ░░ ▒░ ▒░▒░ ░  ▒░   ▒ ▒ 
                      ░   ░   ░ ▒ ▒░ ░  ░      ░  ░  ▒ ▒░ ░  ░░   ░ ▒░
                    ░ ░   ░ ░ ░ ░ ▒  ░      ░   ░ ░  ░ ▒      ░   ░ ░ 
                          ░     ░ ░         ░        ░ ░           ░ 

# GOMON

## Directory and File Watcher && Live Server :: Similar to NODEMON, But can work with any platform.
### You can watch any Directroy and keep any Process Alive. Enjoy!!
## Features:
* You can use with any platform like Nodejs, Golang, Python etc.
* Run any command and Watch any directory.
* Super fase, as built in Golang.
* Easy installation.
* No dependencies.
* Colorfull Info Prompts for readability.
* Available as a debian package.
* Free to use.

## Usage: 
```sh
  SYNTAX:
	gomon -d <directory to be Watched.> -c "command to run"

  EXAMPLES: 
	gomon -d . -c "go run ./main.go"
	gomon -d . -c "go run ./cmd/app/main.go"
	gomon -d ./src -c "node src/app/index.js"
	gomon -d /tmp -c "python script.py"
	gomon -d ./directory -c "./binary"
	gomon -d ../. -c "any command"
```


## Installation
### Method A:
>Using the Debian Package Manager / apt / apt-get.
#### 1. Downlaod the "Binary File":

```sh
curl -O https://github.com/clubcleaver/gomon/raw/main/gomon.deb
```
###### OR
```
wget curl https://github.com/clubcleaver/gomon/raw/main/gomon.deb
```
#### 2. Install the package
```sh
sudo apt install ./gomon.deb
```

> NOTE:
Please make sure you are in the same directory as the gomon.deb file, when running the command.

#### 3. Use GOMON
```sh
gomon
```

---

### Mehod B:
>Manual Install
#### 1. Downlaod the "Binary File":

```sh
curl -O https://github.com/clubcleaver/gomon/raw/main/gomon
```
###### OR
```
wget curl https://github.com/clubcleaver/gomon/raw/main/gomon
```
#### 2. Change file permissions
```sh
chmod 777 ./gomon
```
#### 3. Add the file location to your $PATH.
```sh
export $PATH=$PATH:<path-to-gomon-file>
```
#### 4. Use GOMON
```sh
gomon
```
---



## Reason
Flexibility to use any directory and run any type of file at any location,s using one package.

### Hope you like using GOMON

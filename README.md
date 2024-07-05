# GLIVE

                                  ▄████  ██▓     ██▓ ██▒   █▓▓█████ 
                                ██▒ ▀█▒▓██▒    ▓██▒▓██░   █▒▓█   ▀ 
                                ▒██░▄▄▄░▒██░    ▒██▒ ▓██  █▒░▒███   
                                ░▓█  ██▓▒██░    ░██░  ▒██ █░░▒▓█  ▄ 
                                ░▒▓███▀▒░██████▒░██░   ▒▀█░  ░▒████▒
                                ░▒   ▒ ░ ▒░▓  ░░▓     ░ ▐░  ░░ ▒░ ░
                                  ░   ░ ░ ░ ▒  ░ ▒ ░   ░ ░░   ░ ░  ░
                                ░ ░   ░   ░ ░    ▒ ░     ░░     ░   
                                      ░     ░  ░ ░        ░     ░  ░
                                                        ░          


## Directory and File Watcher && Live Server :: Similar to NODEMON, But can work with any platform.
### You can watch any Directroy and keep any Process Alive. Enjoy!!
## Features:
* You can use with any platform like Nodejs, Golang, Python etc.
* Run any command and Watch any directory.
* Super fast, as built in Golang.
* Easy installation.
* No dependencies.
* Colorfull Info Prompts for readability.
* Available as a debian package.
* Free to use.

## Usage: 
```sh
  SYNTAX:
	glive -d <directory to be Watched.> -c "command to run"

  EXAMPLES: 
	glive -d . -c "go run ./main.go"
	glive -d . -c "go run ./cmd/app/main.go"
	glive -d ./src -c "node src/app/index.js"
	glive -d /tmp -c "python script.py"
	glive -d ./directory -c "./binary"
	glive -d ../. -c "any command"
```


## Installation
### Method A:
>Using the Debian Package Manager / apt / apt-get.
#### 1. Downlaod the "Binary File":

```sh
curl -O https://github.com/clubcleaver/glive/raw/main/glive.deb
```
###### OR
```
wget curl https://github.com/clubcleaver/glive/raw/main/glive.deb
```
#### 2. Install the package
```sh
sudo apt install ./glive.deb
```

> NOTE:
Please make sure you are in the same directory as the glive.deb file, when running the command.

#### 3. Use GLIVE
```sh
glive
```

---

### Mehod B:
>Manual Install
#### 1. Downlaod the "Binary File":

```sh
curl -O https://github.com/clubcleaver/glive/raw/main/glive
```
###### OR
```
wget curl https://github.com/clubcleaver/glive/raw/main/glive
```
#### 2. Change file permissions
```sh
chmod 777 ./glive
```
#### 3. Add the file location to your $PATH.
```sh
export $PATH=$PATH:<path-to-glive-file>
```
#### 4. Use GLIVE
```sh
glive
```
---



## Reason
Flexibility to use any directory and run any type of file at any location,s using one package.

### Hope you like using GLIVE

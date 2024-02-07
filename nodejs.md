**install node && npm version**

update packages:
```bash 
	sudo apt update -y && sudo apt upgrade -y
```

Install curl to be able to install NVM:
```bash
sudo apt install curl 
```
Script Review:
```bash
	curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh
```

We download and execute:
```bash
	curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```

We get script:
```bash
	source ~/.bashrc
```

We ask versions:
```bash
	nvm list-remote
```

We install the desired version:
```bash
	nvm install vx
```

We check the installed version:
```bash
nvm list
```

install npm:
```bash
	sudo apt install npm
```


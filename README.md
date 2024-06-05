# Configuring the environment

### **Ensure your operating system is up to date**
~~~
sudo apt update && sudo apt upgrade
~~~

<br>

### **Install the recommended packages**
~~~
sudo apt install micro htop curl git texlive-base texlive-fonts-recommended texlive-fonts-extra
~~~

<br>

### **Install the code server <sub><sup>(optional)</sup></sub>**
~~~
curl -fsSL https://code-server.dev/install.sh | sh
~~~
<sup>Configure the code server password: .config/code-server/config.yaml</sup>

<br>

### **Change micro exit command**
~~~
"Ctrl-x": "Quit"
~~~
<sup>Configure the micro bindings: .config/micro/bindings.json</sup>

<br>

### **Add aliases to bash terminal shell**
~~~
alias ls="ls -1 --color=auto"
alias la="ls -1A --color=auto"

alias clr="clear"
alias clh=":>~/.bash_history && history -c && clear"
~~~

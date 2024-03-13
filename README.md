# Configuring the environment

### **Ensure your operating system is up to date**
~~~
sudo apt update && sudo apt upgrade
~~~

<br>

### **Install the recommended packages**
~~~
sudo apt install neofetch micro curl git
~~~

<br>

### **Install the code server**
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
alias ls="ls -1"
alias la="ls -1A"

alias clr="clear"
alias clh=":>~/.bash_history && history -c && clear"

alias neo="neofetch"
alias mco="micro"
~~~

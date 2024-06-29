<h1 align='center'>Termux Environment for Android</h1>

<h3>Ensure your operating system is up to date</h3>

~~~
sudo apt update && sudo apt upgrade
~~~

<br>

<h3>Install the essential packages</h3>

~~~
sudo apt install micro htop git
~~~

<br>

<h3>Update micro settings and bindings</h3>

~~~
set colorscheme geany
~~~

~~~
bind Ctrl-x Quit
~~~

<br>

<h3>Update bash terminal aliases</h3>

~~~
alias ls="ls -F1 --color=auto"
alias la="ls -AF1 --color=auto"

alias cl="clear"
alias ch=":>~/.bash_history && history -c && clear"

alias mc="micro"
alias 
~~~
<sup>Configure the bash settings: .bash_aliases</sup>

<br>

<h3>Update termux settings</h3>

~~~
volume-keys = volume
terminal-cursor-style = bar
extra-keys-style = none
extra-keys = []
~~~
<sup>Configure the termux settings: .termux/termux.properties</sup>

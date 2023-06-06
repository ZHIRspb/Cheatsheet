# ⚙ Shell Stabilisation

Используя команду `which python python3` проверяем наличие языка программирования **python**

Затем, используя данную комбинацию команд, стабилизируем оболочку внутри нашей машины:

`python3 -c 'import pty;pty.spawn("/bin/bash")'`

`export TERM = xterm`

**Ctrl + Z**

`stty raw -echo; fg`

**Enter**

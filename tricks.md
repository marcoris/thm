# Trick to get a nicer bash shell:
```
python -c "import pty; pty.spawn('/bin/bash')"

crtl+z

stty raw -echo

[f][g] [enter][enter]

export TERM=xterm
```
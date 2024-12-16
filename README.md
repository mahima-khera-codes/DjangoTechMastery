# Real World Django

> Real World Django applications and their open source codebases for developers to learn from


## How to install on your computer

Make sure you have enough free disk space available. Currently ~12GB are needed.

```bash
# Clone this git repo:
git clone git@github.com:ckrybus/real-world-django.git

cd real-world-django/

# The Django apps are linked to as git submodules.
# This will take some time...(see comment below for possible speedup)
git submodule update --init

# OR If you've got git 2.9+ installed try to run updates in parallel:
# git submodule update --init --jobs 4
```


# First time setup: part 2

1. Follow instructions from [Initial setup of Amazon EC2 Ubuntu instance](https://github.com/valera-rozuvan/howtos/blob/master/initial-setup-amazon-ec2-ubuntu-instance.md).

2. Install Google Chrome:
    - Add GPG key. See [here](https://www.google.com/linuxrepositories/).
    - Add APT repository. See [here](https://wiki.debian.org/DebianRepository/Unofficial).
    - Run `sudo apt-get update && sudo apt-get install google-chrome-stable`

3. Install [NVM](https://github.com/creationix/nvm).

4. Install latest stable version of [Node.js](https://nodejs.org/) using `nvm`.

5. Install [Yarn](https://yarnpkg.com/).

6. Install `tslint` and `typescript` by running:

```
npm install -g tslint typescript
```

7. Install [Visual Studio Code](https://code.visualstudio.com/).

8. Install OpenSSH server if you need to access the machine via SSH:

```
sudo aptitude install openssh-server
```

9. Prevent laptop going to sleep if lid is closed - see [How can I tell Ubuntu to do nothing when I close my laptop lid?](https://askubuntu.com/questions/15520/how-can-i-tell-ubuntu-to-do-nothing-when-i-close-my-laptop-lid).

10. Increase number of system file watchers - see [Increasing the amount of inotify watchers](https://github.com/guard/listen/wiki/Increasing-the-amount-of-inotify-watchers).

11. Alias `ls` to always output full information (`ls -a -h -l`). See [How do I create a permanent Bash alias?](https://askubuntu.com/questions/17536/how-do-i-create-a-permanent-bash-alias).

12. Prettier colors for `ls`. See [trapd00r/LS_COLORS](https://github.com/trapd00r/LS_COLORS).

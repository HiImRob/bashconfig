### Link bashconfig folder to home
> ln -s bashconfig ~/.bashconfig

### Add this to `.bashrc`
> [ -n "$PS1" ] && source ~/.bash_profile;

### Add this to `.bash_profile`
> source ~/.bashconfig/.config_init`

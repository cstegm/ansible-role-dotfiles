# ansible-role-dotfiles

- installs https://github.com/nojhan/liquidprompt
- installs https://github.com/gpakosz/.tmux
- installs .vimrc


Example Playbook:
```
- name: install dotfiles
  hosts: all

  vars:
    homepath: /root
    username: root


  roles: 
    - dotfiles  
```

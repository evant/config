#alias pacman='pacman-color'
alias pm='yaourt --noconfirm'
#alias pm='yaourt'

alias grub-edit='vim /etc/default/grub'
alias grub-update='grub-mkconfig -o /boot/grub/grub.cfg; sudo cat /boot/grub/grub.cfg | grep "menuentry" | cut -d "" -f 2'

alias rlogin='sshfs -o reconnect -C -o workaround=all evant@rlogin.cs.vt.edu:. ~/rlogin'
alias rl='ssh -Y evant@rlogin.cs.vt.edu'
alias urlogin='fusermount -u ~/rlogin'

alias sudo='sudo '
alias blink="ruby -e 'loop{$><<\"\r\x1b[#{31+($.+=1)%7}m#{ARGV[0] || \"BLINK\"}\";sleep 0.08}'"

alias nrs='sudo systemctl restart netctl-auto@wlan0.service'

alias stay-on='xset -dpms; xset s off'

# systemd aliases
alias start='sudo systemctl start'
alias stop='sudo systemctl stop'
alias restart='sudo systemctl restart'
alias enable='sudo systemctl enable'
alias disable='sudo systemctl disable'
alias status='sudo systemctl status'
alias journal='sudo journalctl -xn'

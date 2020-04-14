Place the `tmux-session-status` file in your path (i.e. in ~/.local/bin/tmux-session-status), make it excutable, and add the below line to your .tmux.conf 

```
set -g status-right '#(tmux-session-status)'
```

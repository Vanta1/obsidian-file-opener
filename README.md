One day I got incredibly frustrated with xdg-mime, because I thought it was not detecting my default PDF opener (zathura). Then I thought that it was Obsidian not respecting xdg-mime. Now I've come to blame Electron's ```shell.openPath```/```shell.openExternal``` (don't know which without having access to Obsidian's source code).

So, I've created this (so far) very simple plugin to add an "Open in Zathura" option to the file menu. It run's zathura as a shell command, with the absolute file path. 

I'd like to expand this to be more customizable (see [this](https://github.com/phibr0/obsidian-open-with) plugin, which I've  based the initial outline of this one on), but who knows if that's really worth it anyways. It does it's job perfectly on my machine. 
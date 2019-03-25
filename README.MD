```
  _     ____  ____ ___  _ ____  _____ ____ ____  _
 / \   /  _ \/_   \\  \///  __\/  __//   _Y  _ \/ \  /|
 | |   | / \| /   / \  / |  \/||  \  |  / | / \|| |\ ||
 | |_/\| |-||/   /_ / /  |    /|  /_ |  \_| \_/|| | \||
 \____/\_/ \|\____//_/   \_/\_\\____\\____|____/\_/  \|

```

# Fork of Lazyrecon
I plan to build this out for my own tools soon, the HTML output is pretty sweet. I also included the authors `BBHT` -> `install.sh` tool set I might clean that up as well, as `Lazyrecon` doesn't actually utilize all of them.

# Usage

`./lazyrecon.sh target.com`

# About

This script is intended to automate your reconnaissance process in an organized fashion by performing the following:

- Create a dated folder with recon notes
- Grab subdomains using Sublist3r and certspotter
- Grab a screenshot of responsive hosts 
- Grab the response header
- Perform nmap 
- Perform dirsearch 
- Generate a HTML report with output from the tools above


Shoutout to [@nahamsec](https://github.com/nahamsec/lazyrecon)

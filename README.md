# latex-report
Use (xe)latex to write HUST reports. The good potential is automation.



## Important!

Most solutions are googled from the Internet.

Thanks to the answers and Chinese latex forums!w



## Dependency

Take Archlinux for example:

First, 

```shell
$ pacman -S texlive-most
```

Second, you have to have the `zhnumber` latex macro package installed.



## LaTeX tips

-  In order to make the references and statistics and ToCs to be generated correctly, the `.tex` file should be build twice. A simple script `buildtwice.sh` can help you.
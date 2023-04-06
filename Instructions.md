# COMP100 2023S Lab 04 - InLab Questions
### Deadline Friday, 7 April 2023, 11:50 am


## Explore and Collect the Keys

There is a directory called "maze". Within this directory are more directories and txt files in a seemingly random arrangement. Your task is to search through them and inspect the txt files. Some files contain a congratulations message and a key code, for example: "Congratulations! You found one key: **** rYlXcV ****". When you find a file with a key, use the `cat` and `>>` operators to append the contents of that file to `keysFound.txt`. There are around 10 such keys. You should find at least 5.

You may find the following commands helpful, but are not necessary:
* `tree maze` will show you a graph of all the diretories, subdirectories and files that exist within the maze directory. For example:
```
$ tree maze
maze
├── gcuTa
│   ├── bFMIg.txt
│   └── zCeey
│       ├── AzquVEo.txt
│       ├── fzHiOKs
│       │   ├── EIJJqjs.txt
│       │   └── vWktHP
├── HCoGHYyr.txt
├── xuczVpQmOE
│   ├── DJyrHx
│   │   ├── dByvradqC.txt
│   │   ├── kGFpS
│   │   │   ├── CNJbITFa
│   ├── HGVQd.txt
│   └── ZAcXzg
│       ├── dDjpZyW
│       │   ├── MoGhIdsSj.txt
│       │   └── xgeFN.txt
│       ├── iHLramjG
│       │   ├── bigJdEl.txt
│       ├── JBWeSepFfc.txt
└── ySEhVBPWLp.txt
```
You may have to install the `tree` command. You can do that with `sudo apt-get install tree`  for WSL or Ubuntu and `brew install tree` for MacOS.

* You may also find the `grep` command useful, but is also not necessary.
* For your convenience, a summary of useful shell commands and usage examples are given under `HandyShellCommads.md`
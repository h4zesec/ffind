# ffind - fast find

Note: I have used it for 5 months now on gentoo and I have never had any issues and my searched files were always found within miliseconds. <br>

ffind is an alternative to plocate (and also mlocate) due to them being so bloated. It focues on minimalism, speed and efficiency.

## Installation

You can compile the ffind.c file manually or either run the Makefile provided in the repo.

```
$ make ffind
$ chmod +x ffind
$ chmod +x ffupdate
$ doas cp ffind /bin
$ doas cp ffupdate /bin
```

**Note** : You may edit the CFLAFS or the CC in the Makefile or change the definitions in ffind.h

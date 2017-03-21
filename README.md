Ashaninka Morph
===============

Compiling with XFST
===============================

```
$ xfst -f asheninka.script 
$ xfst -f ideoredupsyl.prq.foma 
$ echo "ashaninka" | lookup -f lookup.script -flags cnKv29TT
Reading script from "lookup.script"
0%>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>100%

  *****  LEXICON LOOK-UP  *****

ashaninka	[a-][NPers][1PL.poss+][--][=shani][VRoot][=to.be.of.the.same.group][--][+NMZ]nka
ashaninka	[a-][NPers][1PL.poss+][--][=shani+m.][NRoot][=anteater][--][+NMZ]
ashaninka	[1PL.S/A+][a-][--][=shani][VRoot][=to.be.of.the.same.group][--][+NMZ]nk[--][+REAL]a
ashaninka	[1PL.S/A+][a-][--][=shani][VRoot][=to.be.of.the.same.group][--][+NMZ]nk[--][+IRR]a
ashaninka	[1PL.S/A+][a-][--][=shani][VRoot][=to.be.of.the.same.group][--][+NMZ]nka


LOOKUP STATISTICS (success with different strategies):
strategy 0:	1 times 	(100.00 %)
strategy 1:	0 times 	(0.00 %)
not found:	0 times 	(0.00 %)

corpus size:	1 word
execution time:	0 sec
speed:		1 word/sec

  *****  END OF LEXICON LOOK-UP  *****

```

How to download
===============

* Using `wget`
```
$ wget https://github.com/hinantin/AshaninkaMorph/archive/master.zip 
```

* Cloning the repository
```
$ git clone https://github.com/hinantin/AshaninkaMorph
```

Software prerequisites
======================

In order to run AshaninkaMorph (this finite state transducer), you will need either Foma or XFST, the download links for these are provided below:

* Foma: https://bitbucket.org/mhulden/foma/downloads (In order to run Foma on a Linux OS you will need to install the following packages first: zlib1g-dev, flex, bison, libreadline-dev).

* XFST: http://www.stanford.edu/~laurik/.book2software/

Software testing
================

Don't know how or want to install it?

Then test it on-line at http://hinantin.in/

For more information
====================

Richard Castro Mamani

E-mail: rcastro@hinant.in

Skype: richardtk_1




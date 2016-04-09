---
layout: post
title: "Trying clojure"
date: 2016-04-09 18:51:52 -0300
comments: true
categories: 
---

Last login: Sat Apr  9 18:01:12 on ttys002
mauricio@Polyphemus ~ $ brew install clojure                                                                                                                                    [ruby-2.2.2]
Error: No available formula with the name "clojure"
Clojure isn't really a program but a library managed as part of a
project and Leiningen is the user interface to that library.

To install Clojure you should install Leiningen:
  brew install leiningen
and then follow the tutorial:
  https://github.com/technomancy/leiningen/blob/stable/doc/TUTORIAL.md
mauricio@Polyphemus ~ $ brew install leiningen                                                                                                                                  [ruby-2.2.2]
==> Downloading https://homebrew.bintray.com/bottles/leiningen-2.6.1.yosemite.bottle.tar.gz
######################################################################## 100.0%
==> Pouring leiningen-2.6.1.yosemite.bottle.tar.gz
==> Caveats
Dependencies will be installed to:
  $HOME/.m2/repository
To play around with Clojure run `lein repl` or `lein help`.

Bash completion has been installed to:
  /usr/local/etc/bash_completion.d

zsh completion has been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/leiningen/2.6.1: 8 files, 14.7M
mauricio@Polyphemus ~ $ mkdir Projects-Clojure                                                                                                                                  [ruby-2.2.2]
mauricio@Polyphemus ~ $ cd Projects-Clojure                                                                                                                                     [ruby-2.2.2]
mauricio@Polyphemus ~/Projects-Clojure $ lein repl                                                                                                                              [ruby-2.2.2]
zsh: correct lein to _lein [nyae]? n

Retrieving org/clojure/tools.nrepl/0.2.12/tools.nrepl-0.2.12.pom from central
Retrieving org/clojure/pom.contrib/0.1.2/pom.contrib-0.1.2.pom from central
Retrieving clojure-complete/clojure-complete/0.2.4/clojure-complete-0.2.4.pom from clojars
Retrieving org/clojure/clojure/1.8.0/clojure-1.8.0.pom from central
Retrieving org/clojure/clojure/1.8.0/clojure-1.8.0.jar from central
Retrieving org/clojure/tools.nrepl/0.2.12/tools.nrepl-0.2.12.jar from central
Retrieving clojure-complete/clojure-complete/0.2.4/clojure-complete-0.2.4.jar from clojars
nREPL server started on port 54993 on host 127.0.0.1 - nrepl://127.0.0.1:54993
REPL-y 0.3.7, nREPL 0.2.12
Clojure 1.8.0
Java HotSpot(TM) 64-Bit Server VM 1.8.0_66-b17
    Docs: (doc function-name-here)
          (find-doc "part-of-name-here")
  Source: (source function-name-here)
 Javadoc: (javadoc java-object-or-class-here)
    Exit: Control+D or (exit) or (quit)
 Results: Stored in vars *1, *2, *3, an exception in *e

user=>

user=>  (+ 1 2 3)
6
user=> Bye for now!
mauricio@Polyphemus ~/Projects-Clojure $ lein repl                                                                                                                              [ruby-2.2.2]
nREPL server started on port 54998 on host 127.0.0.1 - nrepl://127.0.0.1:54998
REPL-y 0.3.7, nREPL 0.2.12
Clojure 1.8.0
Java HotSpot(TM) 64-Bit Server VM 1.8.0_66-b17
    Docs: (doc function-name-here)
          (find-doc "part-of-name-here")
  Source: (source function-name-here)
 Javadoc: (javadoc java-object-or-class-here)
    Exit: Control+D or (exit) or (quit)
 Results: Stored in vars *1, *2, *3, an exception in *e

user=> Bye for now!

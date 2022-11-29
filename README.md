
== forked from https://github.com/ickerwx/pattern ==
with some modifications due to old python version

# Pattern - a reimplementation of pattern\_create/pattern\_offset in Python
Metasploit comes with multiple very convenient scripts and utilities. Among
the most valuable for me are pattern_create and pattern_offset. I found it
increasingly annoying that both have a relatively long startup time.

So after I overheard one of my colleagues complaining about this as well,
I quickly hacked together a Python version that basically does the same.
## Usage
```
$ ./pattern
Usage: pattern (create | offset) <value> <buflen>

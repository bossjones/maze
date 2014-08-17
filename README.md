Maze
====

A fork of the [Maze Sugar Activity](https://git.sugarlabs.org/maze), with speech recognition support.

##Speech Recognition

Speech recognition support is brought to Maze using [sugarlistens](https://github.com/rparrapy/sugarlistens), 
a speech recognition module for the Sugar Learning Platform. The following commands are supported:

* GO UP
* GO DOWN
* TURN LEFT 
* TURN RIGHT
* STOP ACTIVITY
* NEW EASIER GAME 
* NEW HARDER GAME

The supported commands are defined in *speech/en/language.gram* in [JSGF](http://cmusphinx.sourceforge.net/doc/sphinx4/edu/cmu/sphinx/jsgf/JSGFGrammar.html) 
format and the list of valid words is defined by the phonetic dictionary in *speech/en/dictionary.dic*.

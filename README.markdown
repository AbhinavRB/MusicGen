This is a python program that parses music wav files and understands the underlying note framework, or raaga (scale), in order to programmatically generate music that is similar in structure and note progression. It was developed as a writing aid for composers. 

This program is a markov chain based music generator in the Mohanam Raga.
Please see the github [pages](spranesh.github.io/mcmg) for this project for
more.

The simplest way of running the program is

    $ python main.py pieces/*

The default result will be stored in <tt>score_output.txt</tt>.
The program takes various commandline options. Try

    $ python main.py -h

for a listing of all options

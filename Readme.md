iKog - It Keeps on Growing

is a simple todo list: see here http://www.henspace.co.uk/ikog/

This is a fork to improve it with some features I needed.
Currently it has:

*   a bit of code cleaning
*   command line completion
*   LISTF = List to FILE. So that you can do shell things with iKog
*   Better HELP. You can do "HELP LISTF"  to receive what youd expect

Features I want to add:

* regex substitution: so that you can write complex shortcuts, aliases and more.
  No more writing long lines such as 
        @Computer :pmycomputerproject
  It will be enough to write
        ~comp
* output any command to file (what LISTF does) in a unified way
* Huge code cleaning: in order to make it more extensible and more powerful,
  it has to be cleaned. This will even allow to easier porting to Python3
* Library. So that you can import ikog in python and use it "externally". 

This is work in progress, but I use it on my machine regularly :)

PS: note that some features are still not completely available.
Due to some code changes, completion and help is available only for a small
subset of commands

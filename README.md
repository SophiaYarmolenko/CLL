# Command Line Interface
## Goal:
Make an console interface that will execute the selected command and write the command history (with time) to a log file. Sounds ~~not~~ interesting, right?:wink:
## Implementation:
*    Create class CLA (command line analizator) that operate history and has function what we want to do
*    Create class History, which manages all manipulation to history save
*    Create class with [trie](https://en.wikipedia.org/wiki/Trie) that have all command name and pointers to functions what commands mean (it helps to do fast search)
## Existing command
*    ` help ` - show instructions
*    ` quit ` - exit without save
*    ` exit ` - exit with save
*    ` save ` - save command history
*    ` load ` - open file with history
*    ` logfile ` - show file name
*    ` list ` - show your history
*    ` logOn ` - start record history
*    ` logOff ` - stop record history
*    ` logAppend ` - record your history to the back
*    ` logNew ` - clear and start recording new history
*    ` logClearHistory ` - clear your history

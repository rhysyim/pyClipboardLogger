# clipboardLogger
A tool written in Python that logs the text in clipboard that works with Linux, Mac and Windows.

On Linux, the pyperclip module makes use of the xclip or xsel commands, which should come with the os. Run “sudo apt-get install xclip” or “sudo apt-get install xsel” to install the commands. The gtk or PyQt4 modules would be needed otherwise.

Please refer to https://github.com/asweigart/pyperclip for more information about the pyperclip module.

Modules used: 
 -  Pyperclip
 -  Logging
 -  Time

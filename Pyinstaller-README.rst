# is210
IS 210 files

Making a Stand Alone Executable from a Python Script Using PyInstaller
======================================================================
I have Anaconda/Python-3 installed on a Windows 10 PC. 
From a command-line, i ran: pip install pyinstaller
The installation took a few minutes, and only had one warning, but it completed successfully. 

Running Pyinstaller
-------------------
After creating my simple script and saving it <script.py>, from a command-line I changed directory to the script's location (...\.anaconda\navigator\scripts).
I then ran: pyinstaller --onefile <your_script_name>.py    (in my case,  pysintaller --onefile HelloWorld.py)
There was about 50 lines of "... INFO:" produced, with the last one saying "... 32675 INFO: Building EXE from EXE-00.toc completed successfully."

Running the Resulting .EXE File
-------------------------------
I knew from the website where I found out about this module, `https://dzone.com/articles/making-a-stand-alone-executable-from-a-python-scri` that the .exe file
produced would be put into the .\dist directory.
I ran HelloWorld.exe from the command-line and it worked as expected. When I tried from Windows (GUI) it opened a terminal and then closed right away. Needs a pause ...

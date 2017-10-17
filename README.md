# Hack.me
An Open Source Python Package to hack google forms.

### Requirements
In order to use this code, you will require the Python package 'Requests' to be installed.

You can install this by using the following command:

pip install requests

### Instructions
Before running the code you will have to scan the source code of the form. This can be done by using unminify. Using unminify search the form for hidden elements that are used to post the data on form submission.

Once you have completed this step, you will be required to update the URL, the entry.id numbers, and the referer with your desired output from unminify. After the code has been adapted for your current situation, you can run the code using the command 'python gfs.py'. Now the code will loop as many times as you have specified in the code.

Happy hacking!


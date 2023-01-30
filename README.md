# JS-Enumeration
Grab all JS files and look for sensitive data

A script in Python that you can use to grab all the JavaScript files from a list of domains and search for secret files such as hidden endpoints, tokens, API keys, passwords, usernames, etc. and store the results in an outputjs.txt file in a readable format.

This script uses the requests library in Python to make HTTP requests to the websites and the re library to perform regular expression searches on the contents of the JavaScript files.

To run the script, you need to have Python and the requests library installed on your Linux system. You can install the requests library by running pip install requests in your terminal.

You can then run the script by running python script.py in your terminal. The script will read the list of domains from the domains.txt file and write the results to the outputjs.txt file.

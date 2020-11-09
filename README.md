# Database Exploration CLI Tool
A python 2.7 CLI tool created for use at Ecolane that allows viewing, searching, filtering, and exporting with a local or remote MongoDB database.

## Features
* Connect to remote MongoDB server (through SSH tunneling) or local server (hosted on default MongoDB port)
* Select and explore all databases and collections
* Define custom search queries and filters within a collection to be displayed
* Export filtered and unfiltered search results to a CSV file through a mongoexport system call

## Incompleted Features
* Recursively move through nested collections
* Filter and search by objectID

## To Use
* Be sure you have Python 2.7 installed.
* Download `main.py` and run with `py main.py` or `python main.py`.

## Additional Notes
Program was designed for a specific remote database storing shuttle routes that does not have nested collections and supports only Python 2.7. If you would like to use it on your own server, some modification may be required. The code is extensively commented, but there may be some unnecessary debug comments mixed in.

# WAX Account Tag Finder

This Python script finds the Alienworlds tag of a given WAX account by querying multiple API endpoints.

## Requirements

- Python 3.x
- `requests` library

## Usage

1. If you have a .txt file with a list of WAX account names, you can run the script with the file as a command line argument:

    ```
    python aw_tag.py yourfile.txt
    ```

    Replace `yourfile.txt` with the path to your .txt file. The script will read the account names from the file.

2. If you don't have a .txt file, you can run the script without any arguments:

    ```
    python aw_tag.py
    ```

    The script will prompt you to enter the WAX account names, separated by commas.

After finding the tags for all accounts, the script will print the results to the console. It will then ask you if you want to save the results to a file. If you answer 'y', it will write the results to a file named with the current system epoch time followed by '_AW-tags.txt'.

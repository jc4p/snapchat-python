A Python implementation of the Snapchat API.

Current features are solely downloading unread snaps (both images and videos).

# Setup:
Due to the low number of requirements, there is no requirements.txt. The script assumes that both [requests](https://github.com/kennethreitz/requests) and [pycrypto](https://pypi.python.org/pypi/pycrypto) are installed, both of which can easily be installed via:

`pip install requests pycrypto`

# Usage:
Run `python snapchat.py` to see usage help, or run `python snapchat.py USERNAME PASSWORD` to actually use the application.

It will automatically login to Snapchat (logging you out of your current session on a phone, if applicable, due to Snapchat only accepting one session at a time), check for unread snaps, and download any found to the same directory as the file.
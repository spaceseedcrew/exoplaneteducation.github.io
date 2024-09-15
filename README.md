usage: download.py [-h] -e EMAIL -p PASSWORD [-a {of,by}] [-u USERNAME]

Download photos from Facebook

optional arguments:
  -h, --help            show this help message and exit
  -e EMAIL, --email EMAIL
                        Your Facebook email
  -p PASSWORD, --password PASSWORD
                        Your Facebook password
  -a {of,by}, --album {of,by}
                        Photo album to download (default: of). Use "of" to download
                        tagged photos. Use "by" to download uploaded photos.
  -u USERNAME, --username USERNAME
                        Facebook username to download photos from
  -t TIMEOUT, --timeout TIMEOUT
                        Wait this many seconds between photos (default: 2)

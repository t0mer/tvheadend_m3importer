# Obsolete
This functionality is now provided in Tvheadend by adding an "Automatic IPTV network".

# Bulk import from .m3u/.vlc to Tvheadend
A quick script which imports all the files in the given
m3u file to Tvheadend.

Example:
```bash
python channels.py Channels.m3u http://myhost.example.org:9981
```
Example with credentials:
```bash
python channels.py Channels.m3u http://myhost.example.org:9981 --user some_user --password some_password
```
# The MiSTer Manuals DB - RCA Studio II
This is a database for the MiSTer project that downloads the English manuals in .pdf form for the RCA Studio II to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

Or download this .ini file and put it in /media/fat https://github.com/ajgowans/manualsdb-rcastudio/blob/db/downloader_ajgowans_manualsdb-rcastudio.ini


```ini
[ajgowans/manualsdb-rcastudio]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-rcastudio/db/db.json.zip

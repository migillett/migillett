# Nice to meet you! I'm Michael.
- 👋 I'm a husband, father, video producer, DIY believer, and coding hobbyist
- 👨🏻‍🎓 Masters Degree in Management Information Sysems
- 🎥 Bachelor's Degree in Mass Communication
- 🐍 I'm self-taught in Python 3 and specialize in task automation
- 🌱 I’m currently learning about APIs, database integration, and web scraping
- 📹 Check out my [Vimeo Profile](https://vimeo.com/migillett)

## My Favorite Projects

### [LiveLT](https://github.com/migillett/LiveLT)
This Python script allows you to scan QRCodes and transmit them directly to a NewTek Tricaster via their DataLink feature. The script uses PyQt5 for the main GUI and opencv-python for capturing webcam input and QR decoding. Great for live events such as Graduations where making lower thirds for every person is impractical.

### Automatic Video Editing Script
This is a private repository - as it is built for a specific use-case at my work - but it combines FTP pull with the open-source program [FFMPEG](https://ffmpeg.org/) and [MoviePy](https://pypi.org/project/moviepy/) to download, edit, export, and upload content to digital signage. The program uses FFMPEG's blackdetect function to search through the downloaded media file and find the in and out points of black video. The program then cuts that black portion of the video out, drops in a 3-minute PSA break, exports that file, and uploads the finished file to our digital signage server.

### [FTP Pull](https://github.com/migillett/FTP_Pull)
A script to automatically connect to a FTP server and download all files with specific file extensions. Great for downloading commercials or assets from content providers.

### [AJA Kumo Automation](https://github.com/migillett/AJA-Kumo-Automation)
A fork from [szumlins/scripts](https://github.com/szumlins/Scripts), this script allows you to automate the switching of video inputs and outputs on a AJA Kumo 16/16 video router.

### [Blackmagic Videohub Control](https://github.com/migillett/Blackmagic-Videohub-Control)
Allows you to send commands to the Blackmagic Videohubs. Similar to the AJA Kumo Automation, but for Blackmagic.

### [Excuse Generator](https://excusegenerator.anvil.app/)
I was inspired after seeing an Imgur post about an excuse generator in a book. I took the idea and ran with it. This website is built using [Anvil.Works](https://anvil.works), which is a Python3 web application development platform. Users can submit 3 different components: an intro, a scapegoat, and an excuse. This entry is automatically passed through a ["naughty word filter"](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words/blob/master/en) and also sanitized for potential code-breaking characters. The posts are then approved manually by admins. When an excuse is generated, the server selects one of the 3 components at random to create a new excuse. Users have the chance to save the excuse to the highlights page where other users can vote for their favorites. Once every day, the software will remove posts with 0 votes over a certain age to keep the database compact. It will also remove posts that have less than -2 votes to hide the more controversial ones.

It also has an API. Just make a get request to `https://excusegenerator.anvil.app/_/api/excuse` and you'll get a randomly-generated excuse for you to use in your own programs.

### [Easy SQLite3](https://github.com/migillett/Easy_SQLite3)
This script simplifies a lot of the tedium when using a SQLite3 database in new projects. I've adapted a bunch of scripts into one centralized class that is importable and allows you to call functions really easily including converting to and from dictionaries/sql queries.

### [PDF Web Scraper](https://github.com/migillett/PDF-Downloader)
A web-scraping script to download all PDFs from a given URL.

### [RAW to JPEG](https://github.com/migillett/RAW-to-JPEG)
Converts Canon, Sony, and Nikon RAW images into JPEGs for archiving and space efficiency

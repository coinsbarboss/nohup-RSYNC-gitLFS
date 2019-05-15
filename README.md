# nohup ./script.sh &        ->  will survive terminal closure

# rsync -azP -e "ssh -p PORT_NUMBER" source destination



# lsix
Like "ls", but for images. Shows thumbnails in terminal using [sixel](https://en.wikipedia.org/wiki/Sixel)
graphics.




## Usage

    lsix [ FILES ... ]

### Basic Usage

Just typing `lsix` will show images in the current working directory.
You can also specify filenames and, of course, use shell wild cards
(e.g., `lsix *jpg *png`).

Because lsix uses ImageMagick pretty much any image format will be
supported. However, some may be slow to render (like PDF), so lsix
doesn't show them unless you ask specifically. If you want to force a
listing of a certain type of image simply specify the filenames or
use a wildcard (`*.pdf` in the example below),.

![Example 1 of lsix usage](/README.md.d/example1.png "Most basic usage")


Panfolio
--------

Panfolio is a tiny Python script to generate a nice and simple, yet beautiful, gallery of all your (say, vacations) pictures. The only reason I wrote this was to get a free coffee on @artmello, who happens to be quite lazy to organize his photos :-) but hey, it worked fine and I went on a Round The World trip, so all my photos MUST be put online with Panfolio... that's the basic requirement now.

Demo
----

Wanna see how Panfolio looks like? Check it out: http://caio.ueberalles.net/panfolio-demo

Usage
=====

The following command was used to generated the demo gallery. Specifies a caption file for some of the photos, tells Panfolio to look for photos in a test directory, sets the gallery title and url and then marks all blurry photos in the gallery for later inspection:

`./panfolio -c test/captions -d test -n 'Panfolio demo gallery!' -u 'https://github.com/caio1982/panfolio' -b 1`

Below you can see the current help messages of Panfolio:

```
demo@localhost$ ./panfolio
usage: panfolio [-h] [-d DIR] [-n NAME] [-u URL] [-b N] [-f] [-c FILENAME]

optional arguments:
  -h, --help            show this help message and exit
  -d DIR, --dir DIR     your photos directory
  -n NAME, --name NAME  the name of your gallery
  -u URL, --url URL     url to be appended to your gallery
  -b N, --blurry N      mark images whose blurry factor is above N
  -f, --fullscreen      makes a full screen pictures-only gallery
  -c FILENAME, --captions FILENAME
                        reads captions from file and add them to the photos
```

Pros
====

- as simple as it could get
- renders fine in tablets and smarthphones
- no javascript, no images, loads pretty fast
- your pictures matter, no cluttering
- automagically rotates thumbnails
- elegant! css-only mosaic style gallery
- photo captions support
- a minimalist css-only lightbox
- sub-directories support

Cons
====

- no keyboard navigation
- ...other cons? you tell me!

Pending
-------

- merge all css and html into a single file?
- some kind of social networking thing?

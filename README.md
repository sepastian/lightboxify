# Lightbox2

Lightboxify turns a folder containing images into a lightbox slideshow.

## Demo and instructions

Grab a copy of lightboxify from Github

    git clone https://github.com/sepastian/lightboxify

Now, tell *lightboxify* where to find the images to turn into a slideshow and 
where to store the result.

    cd lightboxify
    ./lightboxify /tmp/images/ /tmp/slideshow/

Now, point your browser to `/tmp/slideshow/` to view the result, or copy the
slideshow to your web server.

    scp -r /tmp/slideshow/ user@webserver.com:/var/www/website/

If you like *lightboxify* a lot, or if circumstances have you use it a lot,
you may like to add the script to your search path. Assuming that your `$PATH`
contains `/usr/local/bin`, you can do the following to run *lightboxify* from
everywhere.

    cd lightboxify
    sudo cp lightboxify /usr/local/bin

## Dependencies

*Lightboxify* has been developed and tested on Debian Linux, with the following
dependencies installed.

  * Curl
  * Imagemagick

## Credits and license

### Author
By Sebastian Gassner,
backed by Lokesh Dhakar's awesome
[Lightbox2](https://github.com/lokesh/lightbox2).

###License
Licensed under the [Creative Commons Attribution 2.5 License](http://creativecommons.org/licenses/by/2.5/)

* Free for use in both personal and commercial projects.
* Attribution requires leaving author name, author homepage link, and the license info intact.

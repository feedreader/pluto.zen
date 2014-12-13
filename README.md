# `zen` -  Pluto Planet Template Pack

## What's Pluto?

Pluto is a feed reader that lets you build web pages from published
web feeds. More [Pluto Project Site »](http://feedreader.github.io)


## Usage

### Try It Yourself - How To Use the Zen Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ pluto install zen

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.pluto
    $ git clone git://github.com/planet-templates/planet-zen.git

To check if the new template got installed, use the `list` command:

    $ pluto list

Listing something like:

    Installed templates include:
       top (~/.pluto/zen/zen.txt)

Showtime! Let's use the `-t/--template` switch to build a sample Planet Ruby. Example:

     $ pluto build ruby.ini --template zen     or
     $ pluto b ruby -t zen

Open up the generated planet page `ruby.zen.html` in your browser. Voila. That's it.


## License

The `pluto` scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Planet Pluto and Friends Forum/Mailing List](http://groups.google.com/group/feedreader).
Thanks!

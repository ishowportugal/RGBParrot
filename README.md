# :parrot: RGBParrot(How to install it):

![demo](http://dropit.velvetcache.org.s3.amazonaws.com/jmhobbs/NzczFOYq4g/termbox-parrot-color.gif)

## Installing

Install the RGBParrot.exe or do it from Bash:

```bash
$ go get -u github.com/AmiiHub/RGBParrot
$ terminal-parrot
```
    
### Homebrew

There is a tap for this as well, it's `AmiiHub/RGBParrot`

    brew tap AmiiHub/RGBParrot
    brew install RGBParrot

### Docker

The image is available on [docker hub](https://hub.docker.com/r/jmhobbs/terminal-parrot/)

    docker pull AmiiHub/terminal-parrot
    docker run -it --rm jmhobbs/terminal-parrot:latest

You can also build a docker image locally and run it in a container with...

    docker build -t partyparrot ./
    docker run -it --rm partyparrot (-args)

### Quitting

Hit the escape key to quit.

### -loops

You can limit your parrots enthusiasm with the `-loops` flag.

### :fastparrot:

Set the frame delay with the `-delay` flag (defaults to 75, use 25 for :fastparrot:)

### :aussieparrot:

Use `-orientation aussie` for our friends down under.

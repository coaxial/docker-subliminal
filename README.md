# Subliminal Docker image

Subliminal is a subtitles downloader for your video files. Subliminal is
written by Diaoul, and is available at https://github.com/Diaoul/subliminal

*Note that this is a work in progress*

## Usage

### Basic

Run
``shell
$ docker run coaxial/docker-subliminal /path/to/media/directory
``
to search `/path/to/media/directory` for video files and download their
subtitles.

It will use `en` as the language to search for.

TODO: other options
https://subliminal.readthedocs.io/en/latest/user/cli.html#cli

## Tags

`stable`: latest stable release
`latest`: master branch from https://github.com/Diaoul/subliminal
`1`
`1.0`
`2`
`2.0`

Images are built with Alpine Python 3 for the smallest footprint possible.

## Contributing

If you'd like to contribute, fork the repo and hack away. Pull requests very
welcome!

## Licensing

(c) coaxial, MIT license


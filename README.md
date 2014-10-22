# servelr

A small nodejs script to serve the current directory with livereload.

## Installation

    $ npm install -g servelr

## Usage

    Usage: servelr [options]

    Options:

    -h, --help            output usage information
    -V, --version         output the version number
    -p, --port <port>     specify the port [3000]
    -R, --no-lr           disable livereload server
    -r, --lr-port <port>  specify the livereload port [35729]
    -J, --no-jade         disable jade rendering
    -i, --ignore <regex>  specify regex to exclude files from livereload

## Jade and base path handling
If jade is enabled servelr tries to load `index.jade` for the base path `/`.

## Inspiration

Inspired by [visionmedia's serve](https://github.com/visionmedia/serve/) but with less feature, nevertheless extended with livereload.

## License

[MIT](https://github.com/noxan/servelr/blob/master/LICENSE)

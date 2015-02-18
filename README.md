# Albuminer
`albuminer` is a Python 3 package which uses the [imagine](https://github.com/unrar/imagine) library to find album art for a given
audio file, or directory containing audio files.

## Library
The `Albuminer` class is the core of albuminer's functiioning. It basically uses `imagine` and `mutagen` to find accurate
album covers.

## Interface
The command line interface provided with this package is the `albuminize` command.

Usage:

    $ albuminize [/path/to/file.py or /path/to/directory]

Please remember to **not add a slash** to the end of the path!

Alternative usage:

    $ albuminize
    [manually enter path to file(s) when prompted]

## TODO
An interesting add-on to Albuminer would be a script that adds the `albuminize` binary to the context menu of
audio files or directories containing them.



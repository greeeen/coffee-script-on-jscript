# CoffeeScript on JScript

## What is this?

This is a wrapper of CoffeeScript compiler works on JScript.
No need cygwin!

## What is CoffeeScript?

See http://jashkenas.github.com/coffee-script/ .

## Usage

    Usage: coffee [options] path/to/script.coffee

      -c, --compile      compile to JavaScript and save as .js files
      -o, --output       set the directory for compiled JavaScript
      -j, --join         concatenate the scripts before compiling
      -w, --watch        watch scripts for changes, and recompile
      -p, --print        print the compiled JavaScript to stdout
      -s, --stdio        listen for and compile scripts over stdio
      -e, --eval         compile a string from the command line
      -b, --bare         compile without the top-level function wrapper
      -t, --tokens       print the tokens that the lexer produces
      -v, --version      display CoffeeScript version
      -h, --help         display this help message

## Note

- The file "coffee-script.js" included in this repository is a part of CoffeeScript.
  You can get the latest version of this from the following.

  https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js

- This script works on JScript. So, some functions and objects that can be used by node.js cannot be used.

- Some problems are known in the direct running(without --compile).
  - Can not know the point that the error occurred.
  - Can not treat the arguments of command line.

## License

    Creative Commons Attribution 3.0 Unported (CC BY 3.0)
    http://creativecommons.org/licenses/by/3.0/deed

## Information

Version:    1.4

Repository: https://github.com/thinca/coffee-script-on-jscript

## ChangeLog

Next version

- Added --join option.
- Added --watch option.
- Fixed the error with an empty file.

1.4  2011-07-08

- Improved the handling of error.
- Fixed some behaviors.

1.3  2011-07-08

- Added --tokens option.
- Added --version option.

1.2  2011-07-07

- Added --output option.
- Fixed bug that can not compile.

1.1  2011-07-07

- Directory support.

1.0  2011-07-07

- Initial Version.

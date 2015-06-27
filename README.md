crenv
-----

[Crystal](http://crystal-lang.org/) version manager.

## Install

```
$ git clone https://github.com/pine613/crenv ~/.crenv
$ echo 'export PATH="$HOME/.crenv/bin:$PATH"' >> ~/.bash_profile
$ echo 'eval "$(crenv init -)"' >> ~/.bash_profile
$ exec $SHELL -l
```

## Usage

Please see help.

```
$ crenv help
Usage: crenv <command> [<args>]

Some useful crenv commands are:
   commands    List all available crenv commands
   local       Set or show the local application-specific Crystal version
   global      Set or show the global Crystal version
   shell       Set or show the shell-specific Crystal version
   rehash      Rehash crenv shims (run this after installing executables)
   version     Show the current Crystal version and its origin
   versions    List all Crystal versions available to crenv
   which       Display the full path to an executable
   whence      List all Crystal versions that contain the given executable

See `crenv help <command>' for information on a specific command.
For full documentation, see: https://github.com/pine613/crenv#readme
```

## Acknowledgement

- [riywo](https://github.com/riywo)
crenv is based [ndenv](https://github.com/riywo/ndenv). Thank you.
- [hokaccha](https://github.com/hokaccha)
crenv-install is based [nodebrew](https://github.com/hokaccha/nodebrew). Thank you.

## See also
- [crystalbrew](https://github.com/pine613/crystalbrew)

## License
Please see LICENSE file.

## Author
Pine Mizune
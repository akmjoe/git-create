# Git Create

Git plugin script to initialize a directory with readme.md and a license.

## Getting Started



### Prerequisites

Intended for use on a linux system with bash. Not tested on windows.

### Installing

Copy git-create file to your bin folder and make sure it is executable.
Copy templates folder to your bin folder.

Open the terminal in the directory you want to initialize as a git directory,
and run the command `git create`.

Takes the following optional parameters:
* `-l <license>` Use defined license
* `-r <path-to-remote>` Add a remote origin
* `-f` Force overwrite license
* `-h` Show usage options
* `-v` Display version

To add a license, save it as a plain text file in the [templates](templates/) directory.

The [readme](templates/readme) template can be edited as you wish. {license} will be automatically replaced by the name of the license file.

## Authors

* **Joe Rothrock** - *Initial work* - [akmjoe](https://github.com/akmjoe)

## License

This project is licensed under the GPL License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to [PurpleBooth](https://gist.github.com/PurpleBooth) for the readme template


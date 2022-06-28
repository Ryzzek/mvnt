# mvnt
Pronounced "Movie Night", `mvnt` is a cli app written in bash that lets you query movie, tv show and box office information and also download movies.

## Installation
First clone the repo.
```
$ git clone https://github.com/Ryzzek/mvnt
```
Then cd into directory and run the install script provided (may need to run as root).
```
$ cd mvnt
$ sudo ./install
```
The script will prompt to install some dependencies and it will print the destination of mvnt (which for linux is `/usr/local/bin`).

## Usage
After successful installation you may run the following command for help
```
$ mvnt --help
```
This command will output the following
```
Usage:
  mvnt [OPTIONS] [FLAGS]

Options:
  -m, --menu [c]                Display the main menu with different styles
  -d, --dnld [query]            Download movie with query search and multiple selection
  -t, --theater [s|d]           Display theater releases in two modes (simple/detailed)
  -s, --soon [s|d]              Display coming soon releases in two modes (simple/detailed)
  -tv, --tvshow [query]         Search for a tv show with optional season and episode specification
                                query syntax: [name] [season](optional) [episode](optional)
  -a, --strm [query]            View streaming availability of a movie or show
  -b, --boxo [r|a]              Select between recent box office or highest grossing films ever

  -h, --help                    Show help
  -v, --version                 Show version
```

## Uninstall
Inside the cloned repo directory is an uninstall script and to uninstall run
```
$ sudo ./uninstall
```
That's all you have to do.

## Encountering Persistent Errors
The cli app was made possible with API's and it's not on me if they stop working by some reason.

## Contribution
If you want, you may contribute by either optimizing or adding to the code as you see fit.

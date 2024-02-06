# epic5-scripts

A collection of scripts I've written for [EPIC](http://www.epicsol.org) over the years.

The scripts here can be used standalone with no other dependencies aside from EPIC. If you're looking for a more complete script pack, check out my project [DarkStar](https://darkstar.epicsol.org) ([github](https://github.com/bweiss/darkstar)).

Some of these scripts are also included with the EPIC5 distribution.

## How to use

To use a script, start EPIC and issue a `/LOAD` command e.g. `/LOAD ~/epic5-scripts/scripts/tabkey.irc`

To load something automatically at startup, you can add the command to your ~/.epicrc file.

## Scripts

| Filename        | Description                                             |
|-----------------|---------------------------------------------------------|
| autocycle.irc   | Automatically cycle op-less, empty channels to gain ops |
| dotepicrc       | Sample .epicrc file                                     |
| loadformats.irc | Adds customizeable formatting to EPIC5                  |
| nickmgr.irc     | Nick management script                                  |
| tabkey.irc      | Advanced tab key completion                             |

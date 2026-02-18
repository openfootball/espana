# España • Spain

## What's `football.db`?

A free open public domain football database & schema
for use in any (programming) language
(e.g. uses plain text data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for España (Spain) / Europe.
Events include:

| Level |                                    |           |
| ----: | ---------------------------------- | --------- |
|     I | Primera División / La Liga         | 20 Clubs  |
|    II | Segunda División / Liga Adelante   | 22 Clubs  |


Example:


```
= Primera División de España    

▪ Matchday 1
Sat Aug 23
  Málaga CF       1-0  Athletic Bilbao
  Sevilla FC      1-1  Valencia CF
  Granada CF      2-1  Deportivo La Coruña
  UD Almería      1-1  RCD Espanyol
Sun Aug 24
  SD Eibar        1-0  Real Sociedad
  Celta Vigo      3-1  Getafe CF
  FC Barcelona    3-0  Elche CF
  Levante UD      0-2  Villarreal CF
Mon Aug 25
  Real Madrid     2-0  Córdoba CF
  Rayo Vallecano  0-0  Atlético Madrid

...
```


## Build Your Own `espana.db` Copy

Use the `sportdb` command line tool to build your own `espana.db` copy
from the plain text datasets. [More »](https://github.com/openfootball/datafile)


### Alternative I - Use the Quick Starter Templates

Use the quick starter datafile templates to start from scratch. Examples:

Build the database for all Spanish clubs, leagues and seasons:

    $ sportdb new es

Build the database for the 2020/21 season:

    $ sportdb new es2020-21

[More »](https://github.com/openfootball/quick-starter)



### Alternative II - Do-It-Yourself (DIY) - Downlad and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/espana`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db` and
- read in all datasets in plain text (`.txt`)

That's it.



## Questions? Comments?

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)


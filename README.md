# España (Spain)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for España (Spain) / Europe. Events include:

| Level |                                |            |
| ----- | ------------------------------ | ---------- |
| I     |  Primera División / La Liga    |  20 Clubs  |


Example:

~~~
### La Liga - Primera División de España Teams

barcelona, Barcelona|FC Barcelona|Fútbol Club Barcelona,           BAR, city:barcelona
madrid,    Real Madrid|Real Madrid CF|Real Madrid Club de Fútbol,  RMD, city:madrid
...
~~~

~~~
### La Liga - Primera División de España

Jornada 1 / Sáb. 18 y Dom. 19 Agosto

19.08. 19:00  Real Madrid    Valencia CF     1-1
19.08. 21:00  FC Barcelona   Real Sociedad   5-1
...
~~~


## Build Your Own `football.db` Copy

To build your own `football.db` copy from the plain text fixtures
use the sportdb command line tool. Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `es-espana` fixtures

    $ git clone git://github.com/openfootball/es-espana.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./es-espana --worldinclude ./world.db

That's it. For more
see the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby).



## Links

### Web Admin App

Try the `football.db` Web Admin app running on Heroku
[`footballdb.herokuapp.com/es`](http://footballdb.herokuapp.com/es).

### La Liga / Primera División de España

Official Site - [`www.lfp.es` (es)](http://www.lfp.es)

- 20 Teams
- 38 Rounds (19 x 2) - 10 matches per round
- 380 Matches (= 19 x 2 x 10)



#### Wikipedia

- [La_Liga](http://en.wikipedia.org/wiki/La_Liga)
- [2013–14_La_Liga](http://en.wikipedia.org/wiki/2013–14_La_Liga)
- [2012–13_La_Liga](http://en.wikipedia.org/wiki/2012–13_La_Liga)

---

- [Primera_División_de_España (es)](http://es.wikipedia.org/wiki/Primera_División_de_España)
- [Primera_División_de_España_2013/14 (es)](http://es.wikipedia.org/wiki/Primera_División_de_España_2013/14)
- [Primera_División_de_España_2012/13 (es)](http://es.wikipedia.org/wiki/Primera_División_de_España_2012/13)


## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!



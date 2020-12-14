# Flask TODO list

This is my first project with Flask and MySQL.

There's no mucho that I can say about it, it'smore like a small-big test of all this stuff, and it was funny to code this.

If you want to test it, remember to define the os.environ variables on the ***\_\_init\_\_.py*** file!

> $ export FLASK\_APP=todo\
> $ export FLASK\_ENV=development\
> $ export FLASK\_DATABASE\_HOST='localhost'\
> $ export FLASK\_DATABASE\_PASSWORD='password'\
> $ export FLASK\_DATABASE\_USER='user'\
> $ export FLASK\_DATABASE='database'

Also, you need to suscribe the ***init\_db\_command*** defined on ***todo/db.py*** to the app

> $ flask init-db

then you can jusr run flask with
> $ flask run

and open your localhost on any browser and use the app.


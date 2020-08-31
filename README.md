# e14a-2020
Harvard DCE CSCI E-14A Building Interactive Web Applications for Data Analysis

## Labs
*N.b. If you need help troubleshooting during lab, just ask! If you need help afterwards, first perform some early research using Google which will probably lead you to StackOverflow or Github issues; if no clear answer appears, please post your problem publicly and clearly on Piazza - often the most useful guidance arrives from peers.*

#### Schedule
+ **Wk.0** - Initial setup.

#### Initial setup
For labs we will be using several technologies - to avoid any system-specific  hiccups, we highly recommend you install or setup the following in advance:
1. An IDE (ingegrated development environment) or code editor.
    + [PyCharm](https://www.jetbrains.com/pycharm/) is a paid subscription (but offers a free 1 year subscription for
  students) that brands itself as "The python IDE for professional developers".
    + [Sublime Text](https://www.sublimetext.com/) is a free and "sophisticated text editor for
code, markup and prose".
2. A [Github](https://github.com/) account for version control.
    + Signup for the [Student Developer Pack](https://education.github.com/pack) to get loads of free goodies.
    + Install Git on your computer - there is pretty good direction from [Github Help](https://help.github.com/en/github/getting-started-with-github/set-up-git) on setup.
    + It's also worthwhile setting up connection via [SSH](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh).
3. The [Anaconda](https://www.anaconda.com/products/individual) distribution for Python and data science.
    + [Install](https://docs.anaconda.com/anaconda/install/) Anaconda (full version) or Miniconda (mini version) on
     MacOS, Windows or Linux.
4. [Heroku](https://www.heroku.com/) for deployment.
    + Setup a [free account](https://signup.heroku.com/login).
    + Please follow this [guide](https://devcenter.heroku.com/articles/heroku-cli) to setup Heroku's CLI (command
 line interface).
5. [PostgreSQL](https://www.postgresql.org/): The World's Most Advanced Open Source Relational Database.
    + Follow the tutorials: [installation](https://www.postgresqltutorial.com/install-postgresql/) and [connection](https://www.postgresqltutorial.com/connect-to-postgresql-database/)
    + Download the latest version of Postgres from [EDB](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads), which includes: PostgresSQL Server, pgAdmin 4, Stack Builder, Command Line Tools
        + OR, Mac users may want to use [Homebrew](https://wiki.postgresql.org/wiki/Homebrew) for installation.
        + OR, another Mac alternative is to download [Postgres App](https://postgresapp.com/)
    + Confirm success: 
        + For EDB, by opening SQL Shell (psql), and entering: `SELECT version();`
        + For homebrew, in terminal: `psql postgres`
        + For Postgres App, open application.
 
 
 
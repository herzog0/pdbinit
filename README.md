# pdbinit
Script to setup environment, create and initialize Postgres databases (for Ubuntu based distributions) using pgsql.

It will download the source files of pgsql to a folder named `$HOME/Softwares/<postgres version name>`. 



# Installation 
Not required, simply clone the repository and, for better usage, make a soft link to `/usr/bin`:

`ln -s /path/to/pdbinit /usr/bin`

This way you can use the script wherever you are.

# Usage

Call *pdbinit* with *sudo*.

Specify a database name and scripts to initialize the database. 

Some require extensions and roles.
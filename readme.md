This is a shared set of functions.  


To use these functions

##  Clone the repository anywhere you would like. 
##  Add the following to you .bashrc or .bash_profile (Make sure to include the public folder only)

```

BASH_DIR="/full/path/to/this-repo/public"

for f in $(ls  $BASH_DIR);
   do source $BASH_DIR$f;
done

```

##  Source your profile or start a new terminal session.

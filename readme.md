# This is a shared set of functions.  To use these functions:

##  Clone the repository anywhere you would like. 
##  Add the following to you .bashrc or .bash_profile (Make sure to include the public folder only) before any alias or function declarations that you have.  


```
export repo="~/repo/"
BASH_DIR="/full/path/to/this-repo/public"

for f in $(find $BASH_DIR -maxdepth 1 -type f);
   do source $f;
done

```

##  Source your profile or start a new terminal session.

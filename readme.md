This is a set of functions that can be used by all SM personnel.  



To use these functions
1. Clone the repository anywhere you would like. 
2. Add the following to you .bashrc or .bash_profile

```

BASH_DIR="/full/path/to/this-repo"

for f in $(ls  $BASH_DIR);
   do source $BASH_DIR$f;
done

```

3. Source your profile or start a new terminal session.

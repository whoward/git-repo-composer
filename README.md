# git-repo-composer

An example of building a stepped "tutorial style" git repository using a simple bash script and rsync.

To build the git repository just run `./build` in the project directory.  The concept is that you only store 
updated files in each step directory.  There is no way currently to delete files between steps, but if you 
want I'm sure you can figure out a way to do it.

If you are comfortable enough with patch files this could be modified to work with `git apply` which may or
may not be more practical in the long run based on your needs.

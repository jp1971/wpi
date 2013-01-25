w(ord)p(ress)i(nstall)
======================

Description
-----------

wpi is a bash script that automates installing WordPress from the command line.  If you install WordPress on a regular basis, I suggest installing it in your user path somewhere such as `/usr/local/bin/`.

Usage
-----
* Download this repository and install wpi somehwere in your user path (e.g. `/usr/local/bin/`).
* Change the script's permissions so that it is executable (i.e. `chmod +x wpi`).
* Create a directory in which you want to install WordPress.
* `cd` into this directory.
* Issue the `wpi` command.

What the Script Does
--------------------
1. Downloads the latest tarball of WordPress.
2. Untars the archive.
3. Moves the WordPress installation from the `wordpress` directory to the current directory.
4. Deletes the archive and the empty wordpress directory.

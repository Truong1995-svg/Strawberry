=== Strawberry Perl (64-bit) Portable 5.40.0.1-64bit README ===

What is Strawberry Perl Portable?
---------------------------------

* 'Perl' is a programming language suitable for writing simple scripts as well
  as complex applications. See https://perldoc.perl.org/perlintro.html

* 'Strawberry Perl' is a perl environment for Microsoft Windows containing all
  you need to run and develop perl applications. It is designed to be as close
  as possible to perl environment on UNIX systems. See https://strawberryperl.com/

* 'Strawberry Perl Portable' is Strawberry Perl that you do not need to install,
  you do not need admin privileges, you just extract provided ZIP on your disk.
 
How to use Strawberry Perl Portable?
------------------------------------

* Extract strawberry portable ZIP into e.g. c:\myperl\ 
  Note: choose a directory name without spaces and non us-ascii characters

* Launch c:\myperl\portableshell.bat - it should open a command prompt window

* In the command prompt window you can:

  1. run any perl script by launching
  
     c:\> perl c:\path\to\script.pl

  2. install additional perl modules (libraries) from https://www.metacpan.org/ by

     c:\> cpanm Module::Name
  
  3. run other tools included in strawberry like: perldoc, gcc, gmake ...

* If you want to use Strawberry Perl Portable not only from portableshell.bat,
  add c:\myperl\perl\site\bin, c:\myperl\perl\bin, and c:\myperl\c\bin
  to PATH variable

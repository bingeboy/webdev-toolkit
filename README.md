webdev-toolkit
==============
Forgive me its 3am here and I'm just laying down soemthign to work off of. I'm by know means fully versed in all sections covered so please add your expertise.
Growing list of recources like short cuts, files setup, code patterns and other day to day tools that I like at my finger tips.

***
##Table of Contents
1. bash
2. <a href="/wiki/VIM">vim</a>
3. [a link](./VIM)javascipt
4. clientjs
4. nodejs

@Dshaw
http://www.youtube.com/watch?v=ET2N1NtRpHE

Max Ogden
http://youtu.be/VYVXNN7xYw8

5. css
6. api

***

sources:




***
##1. bash

Keys:

jump to beginning of line
    contrl + r 

contrl + e = jump to end of the line
tab = autocompletes as much as possible.

Commands:
``` 
    $cd  = Change directory
    $cd ../ = Parent directory
    $mkdir = Make directory
    $touch = Make file
    $ls = list current 
    $nslookup = lookup domain
    $cat = logs to screen
    $telnet ip port
    $top = view active processes
    $pbcopy < ~/.ssh/id_rsa.pub = copy path
    $rm = remove
    $rm -rf = recusively remove
    $curl
    $ssh
    $spc
	$rsync
``` 



Bash SVN

Bash Git

``` 
git status = status of git
git add * = add file to git
git commit * -m = commmit files with emssage
git push = push to active branch
git pull = pull from active branch

``` 
Git alias the are very help!

Add and commit in a single line:

``` 
git config --global alias.add-co '!git add -A && git commit'

``` 

Links to good dotfiles:
https://github.com/paulirish/dotfiles
http://dotfiles.github.io/

***

 2. VIM
 
 Here are a few vim commands I use.

``` 
i = insert
a = insert after
o = new line after
O = new line before
gg = begining of file
G = end of file
yy = copy line
dd = delete line
d10 = delete 10 lines
p = paste
:w = write file
:q = quit
:q! = force quite
/ = search
u = undo
U = Undo All
Ctrl + r = Redo
:e filename

``` 

### Require Extras
``` 
:JSHint = hints js

``` 

***

3. javascipt 

####targeting obj

Quick and basic:

append methods 
var x = document.getElementById('user-links');

prepend methods


//largest value in array
Array.max = function( array ){
    return Math.max.apply( Math, array );
};

URLS:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference

JS Common frameworks
http://underscorejs.org/
http://requirejs.org/
http://emberjs.com/
http://dojotoolkit.org/
http://jquery.com/

Geolocation:

WebGl:
http://threejs.org/

Plugins Tools:
http://eightmedia.github.io/hammer.js/
http://browserify.org/

Merging arrays
https://gist.github.com/bingeboy/5692603

Merging objects
mergins array with obj
merging object with array

getting length or obj

sorting arra small-large
sorting arra large-small

***

4. nodejs


List out node core exmaple code.



***

5. css

Links to css3 tools.
css3please etc




***

6. API



Maps examples.
Twilio Examples
Twitter Examples



*** 

7. HTML

Clearfix:
https://gist.github.com/bingeboy/5608727


Common Api's i've used some sample code calls.

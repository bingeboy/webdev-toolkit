webdev-toolkit
==============

Adding useful links, snippets; basically anything web dev related.

[Mark Down Editor](http://mouapp.com/)

***
##Table of Contents

<<<<<<< HEAD
##Videos to Checkout
@Dshaw
http://www.youtube.com/watch?v=ET2N1NtRpHE
=======
I bash
II [vim](#vim)
III [JavaSCript](#javascript)
IV [nodejs](#nodejs)
V
VI. css
VII. api
VIII.
>>>>>>> e358b34ae9695691ffa521521636f0c45e6b0a1f


<<<<<<< HEAD
Substack
http://www.youtube.com/user/substack

5. css
6. api
=======
Tools:
(#javascript)

>>>>>>> e358b34ae9695691ffa521521636f0c45e6b0a1f

***

sources:

[Screen Sizes](http://screensiz.es/phone)


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
	$ cat [filename] | pbcopy <~ Great clipboad util.
``` 



Bash SVN

Bash Git

``` 
git status = status of git
git add * = add file to git
git commit * -m = commmit files with emssage
git push = push to active branch
git pull = pull from active branch
git stash = stash your work so you can merge.

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

 II. VIM
 
 ![VIM LOGO](http://www.math.cmu.edu/~gautam/share/vim.png)
 
 Here are a few vim commands I use.

``` 
i = insert
I = I forgot what this one does
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
esc / v = visualmode

``` 

Discover why VIM is so powerful and widely available. 

### Videos
Vim Training Class 2 - Basic motions and commands
<http://www.youtube.com/watch?v=Nim4_f5QUxA&list=PLlqTZ1ulTJiAQYGdZ48eacMs0IWi5ecpn&index=1>

Vim Training Class 4 - Customizing and Extending Vim
<http://www.youtube.com/watch?v=2pqipq-UEwQ&list=PLlqTZ1ulTJiAQYGdZ48eacMs0IWi5ecpn&index=2>



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

##nodejs

https://ci.testling.com/

request
engine.io
twit



List out node core exmaple code.

###Videos
@Dshaw
[http://www.youtube.com/watch?v=ET2N1NtRpHE](http://www.youtube.com/watch?v=ET2N1NtRpHE)

Max Ogden
[http://youtu.be/VYVXNN7xYw8](http://youtu.be/VYVXNN7xYw8)



***

## css

Links to css3 tools.
css3please etc




***

## API

[List of APIs](https://gist.github.com/afeld/4952991)

See also:
[NYC DATA](https://nycopendata.socrata.com/)
Dropbox
Apigee App Services
jsonp.jit.su
popular APIs on ProgrammableWeb
Webshell


*** 

## HTML

Clearfix:
https://gist.github.com/bingeboy/5608727



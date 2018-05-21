# hello-world

Hi Humans !

Hobot here, I like Node.js and Coffeescript (that's what I'm made of),
I've had tacos on the moon and find them far superior to Earth tacos.

So having gone through the simple tutorial to generate the above silly
text, the repository was cloned to a local machine.

Then some simple code folder was added, on a new branch, locally.
1. git checkuout -b helloworld
2. git add .
3. git commit -m "added hello-world code folder"

Then that branch was pushed back to github
1. git push origin helloworld

So now on github web page a beance has been created to document the above, 
consisting of these edits detailing the command line.

THis is done to see how the local command-line interacts with github:
* will the remote (github web page) branch and edits be visible?
* how to get them?
Okay so used the following in the local shell:
1. git remote -v
2. git fetch origin

So #1 showed a fetch and push named origin pointing to the repository on github. excellent.
Well that #2 did NOT fetch the UNCOMMITTED new branch...but maybe that is the point!

So now commit this branch and repeat the #2 to update the local copy...

It is not that the remote branches are invisible, in fact, they are available at the local
Use this to see them all
1. git branch -a
use this to just look at one
1. git checkout master/some-branch
use this to work on a branch
1. git checkout some-branch

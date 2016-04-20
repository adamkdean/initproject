# initproject

Handy script for initialising projects (mkdir, cd, touch, git init, git add, git commit, git remote add, git push)

## Why?

I create a lot of projects, and don't always use GitHub. I've spent most of my adult life typing:

    mkdir example
    cd example
    touch README.md
    git init
    git add .
    git commit -m "Initial commit"
    git remote add origin git@genericscmhost.com:namespace/project.git
    git push -u origin master
    
So I've decided, it has to stop.

## How to do the thing

To use it, copy the script to your local bin directory, say, `/usr/local/bin`, and make sure to `chmod +x` it, then you use it like so:

    $ initproject example git@bitbucket.org:adamkdean/example.git
    
## Licence

MIT

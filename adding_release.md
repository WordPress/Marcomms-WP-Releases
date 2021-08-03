# add a submodule 


This clones the main repo down:
`git clone git@github.com:wpmarketingteam/WP-Releases.git`

This enters the directory:
`cd WP-Releases/`

This makes us a nice 5.6 directory to house this:
`mkdir 5.6`

This puts the command line in the right directory:
`cd 5.6/`

This clones the sub module in:
`git clone git@github.com:wpmarketingteam/WP5.6Marcomms.git`

This tell git about the sub module:
`git submodule add https://github.com/wpmarketingteam/WP5.6Marcomms 5.6/WP5.6Marcomms/`

This adds EVERTYTHING that has been changed " . " is a bad way to do this: 
`git add .`

This saves what we just did to the git history: 
`git commit -m "adding in symlink"`

This pushes it back up to github: 
`git push`
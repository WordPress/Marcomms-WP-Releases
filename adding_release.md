# add a submodule 

`git clone git@github.com:wpmarketingteam/WP-Releases.git`

`cd WP-Releases/`

`mkdir 5.6`

`cd 5.6/`

`git clone git@github.com:wpmarketingteam/WP5.6Marcomms.git`


`git submodule add https://github.com/wpmarketingteam/WP5.6Marcomms 5.6/WP5.6Marcomms/`

`git add .`

`git commit -m "adding in symlink"`

`git push`
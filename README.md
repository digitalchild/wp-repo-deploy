## WP-REPO-DEPLOY

Deploy your wordpress plugin to the wordpress.org SVN repository from your git repository. 

This is a modification of Brent Sheperds [deploy script](https://github.com/thenbrent/multisite-user-management/blob/master/deploy.sh) which is a modification of Dean Clatworthy's [deploy script](https://github.com/deanc/wordpress-plugin-git-svn) 

The wordpress plugin repository requires that you check your plugin code into an SVN repository, while many developers have moved to using Git. This script allows you to deploy your wordpress plugin from Git without maintaining a local SVN repo at the same time. This is a cleaner approach to wordpress plugin deployment than the original script. 

This has been modified to work on OS X instead of linux. 


classic-no-archives
===================

The classic Octopress theme modified so the index page shows a list of archived posts instead of the posts themselves. Links in the navigation bar are removed since they are redundant.

###Install
	$ cd octopress 
	$ git clone git://github.com/laurenceman/classic-no-archives.git .themes/classic-no-archives
	$ rake install['classic-no-archives']
	$ rake generate
	
Since the recent posts sidebar section isn't needed anymore, you may also want edit `_config.yml` by scrolling down to `default_asides` and removing the `asides/recent_posts.html`.
	
	
	



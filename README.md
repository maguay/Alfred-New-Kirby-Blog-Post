This is a tweaked version of [Mark Jenkins' Alfred 2 workflow](http://plausiblethought.net/creating-new-blog-posts-with-an-alfred-workflow) for creating new posts in [Kirby CMS](http://getkirby.com/). Before use, you'll need to add your site's folder path to the beginning of both scripts.

You can [download the workflow directly](https://github.com/maguay/Alfred-New-Kirby-Blog-Post/raw/master/New%20Kirby%20blog%20post.alfredworkflow), or look at the [/Alfred Workflow Files/info.plist](https://github.com/maguay/Alfred-New-Kirby-Blog-Post/blob/master/Alfred%20Workflow%20Files/info.plist) file to see what makes it tick.

This workflow lets you enter the title of a new post in Alfred to create a new, iterated folder for your post (not including your feed folder) with your post name using dashes instead of spaces, and an article.md file for your post. The post text file will open automatically with the title and date already included.

You can also create a link post (saved as article.link.md) using this workflow, which will grab the contents of your clipboard and save it as the link in the post. You'll just need to have the link you want to blog about copied to your clipboard before you start creating the new post in Alfred.

Obviously, this works best for the way I blog: I have my Kirby site set to use the .md format for articles, and also have my blog designed to allow normal text posts as well as link posts, which on my site are saved as article.link.md (see the Kirby tutorial on [custom post types](http://getkirby.com/blog/custom-post-types) for more info on setting this up for your site). I also prefer having an extra line break between each section of articles (the title, date, link, and text), so I added that to the scripts here. You can tweak this as you need for your site style.

Tweaked by Matthew Guay - [Techinch.com](http://techinch.com/).
# Speck 

## Flat file blog engine with markdown support

- No db
- No admin
- Unlimited nesting for posts folders.
- Race condition free caching to withstand high traffic.
- Plain Html templates, simple but still powerfull, powered by [Psttt! template engine](http://github.com/givanz/psttt). 
- Bootstrap 4 default theme
- Disqus/Facebook comments 
- Rss Feed, Tags, Posts Archives 


### Requirements

- PHP 5.3.6+


### Installation

1. Download speck either from [here](http://github.com/givanz/speck) or by cloning this Github repo or by running:
2. Upload speck through FTP/SFTP or whatever upload method you prefer to the public-facing directory of your site.
3. Ensure that the permissions for the `cache` and `posts` folders are set to `0777`.
4. Navigate your browser to your speck installation URL, if you have placed speck in a sub directory make sure you append the folder name to the URL: `http://MYDOMAINNAME.com/speck`
5. Upload markdown files to `posts` folder, choose any folder structure you want to reflect as blog categories.

**No Connect** is a template for the [Jekyll static site generator](http://jekyllrb.com/) that works on
a local machine or a USB key, without an html server. Our template is based on the standard Jekyll theme. Visit us at Columbia's [Group for
Experimental Methods in the
Humanities](http://xpmethod.plaintext.in/) to learn more about our group.

## Motivation
This modification of the main Jekyll theme is part of our effort to investigate minimal computing technologies, and their possible use in humanistic work. Not all forms of scholarship can be shared on the internet, whether the reason is an unfriendly government or copyright regimes. Tapping into the affordances of [Sneakernets](https://en.wikipedia.org/wiki/Sneakernet), is one of the ways we can carve out space for digital work to continue under adverse circumstances. 

## How to use
No-connect won't work on Github pages or on your local machine running a server. The _site folder it generates is meant to be used on a USB (or any other folder with a stable base url). To make it work for your USB you must set the baseurl on your _config.yml to reflect the name of your USB. In our case this is `file:///Volumes/no-connect.` Replace `no-connect` in our example with the name of your USB. 

Once you generate the site using `jekyll build`, copy the contents of the `_site` folder into your USB, and you're ready to go. We recommend that you create a README file in your site that would explain to beginners that they need to double-click the index.html to launch the site. Alternatively, you could simply have a copy of it called START-HERE, or some such thing.

To learn more about how to use Jekyll visit [their excellent documentation](http://jekyllrb.com/docs/home/). Although the end result would work on any machine, note that the Jekyll engine itself runs on Macs and Linux. Windows users have a range of options for static site generation, and we encourage you to explore them. 


## Related Resources

- http://stackoverflow.com/questions/26778329/running-jekyll-generated-files-without-jekyll-local-server

- http://stackoverflow.com/questions/16316311/github-pages-and-relative-paths


![Astro Hack Week](https://img.shields.io/badge/Astro-Hack%20Week-green.svg?style=flat-square)

# AuthoreaOffline
Compile Authorea documents offline and make them still look good online. 

## Hack idea
The people at Authorea are doing fun things with the way scientific documents are written and their integration with GitHub is good. One of the quirks for me, though, is having to work online. There have been attempts to bring the process offline but they break down as the articles get bigger, mostly because Authorea requires a strict repository organization. I would like to improve the Python script written by Erik Tollerud to build the documents offline and keep a working version online in Authorea. To make a working hack I think Python should be enough but any suggestion from someone who knows more LaTeX than I do can be useful.


## What's done already

From the page here: https://www.authorea.com/users/3/articles/17235/_show_article

### Linking up Authorea and Github. 

From your article (main view):
 - Make sure you are an admin (if not, ask the lead author to make you so)
 - Click on the gear icon (Settings)
 - Scroll down to the Advanced Settings and click on `Setup Github Integration` under Offline mode
 - In the page that opens up, click on the big button `Setup Github integration automatically`

**This works!**

Authorea created a repository on my Github account [here](https://github.com/j-faria/Authorea-Offline).
The default article has some `.tex` files, a `bibliography` folder and a `figures` folder. It also has the all-mighty `layout.md` file which is very important! 




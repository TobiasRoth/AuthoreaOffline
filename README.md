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

We can go ahead and clone this repository and/or edit the `.tex` files online. Every change should be updated to the Authorea article. 

But we have no way to compile the code offline. The guide tells us

  LaTeX users. Most users who write in LaTeX will want to compile their articles from time to time when working offline. We advise users not to change the basic structure of the repository. For example, the file layout.md is crucial as it instructs Authorea what files to render. If you delete it, the Authorea article will break! In order to build your article locally when working offline we suggest to use this Python [script](https://github.com/eteq/authorea-scripts) by our fellow Erik Tollerud.




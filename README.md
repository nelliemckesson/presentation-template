# Atlas presentation template

This is a template for a presentation in Atlas.  

## Getting the template into Atlas

In this pre-release version of Atlas, the first step in using the template is to get a fresh copy of it into your GitHub account.  To do this, you'll need to clone the repository to your local machine, like this:

```
$ git clone --shallow https://github.com/oreillymedia/presentation-template.git <your presentation name>
````

(Be sure to use the "--shallow" option so that you don't get the version history.)  Once you download the template, you should create a new project on GitHub, and then add a remote on your local machine to your new presentation.  For example:

```
$ git remote add github git@github.com:aliginedleft/scatteredtoscatterplot.git
$ git push gihub master
```

Once you've pushed the new repo up, you can open it in Atlas.

## Working in Atlas

Once in Atlas, you have a number of options for how you arrange your content.  For example, you can put all your slides in their individual files, or you can put them all together in a single file.  Regardless of your approach, the content of each slide must be wrapped in a "chapter" section.  The "sample.html" file in this repo will show you an example.

You can put any kind of content on a slide:

* plain text
* lists
* tables
* hyperlinks
* images
 
You can also use the "Insert Media" button to insert the HTML markup for:
* YouTube or Vimeo videos
* JSBins
* Google form widgets (these are a simple way to have an interactive poll or form for your viewers)
* Arbitratray iframes

The "sample.html" file will give you some ideas to try.

## Creating an index page

## Viewing the site on your local machine


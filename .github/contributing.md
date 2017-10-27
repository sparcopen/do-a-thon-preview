# Tech contributing

## How to contribute

This is intended a minor, both in code & set up, to the [live doathon site](http://doathon.opencon2017.org/). It's here mainly for testing purposes as coding is hard, we're not great at it, and we'll need to make changes while people are actively using the site (yay agile).

If you have a non-trival edit to the site (and perhaps, even if it is trivial) make it here. Then, check that it all works okay [here](https://sparcopen.github.io/doathon-dev/). If that's good, then go to the same file on the main doathon site and make those same changes.Then, when it's released we know it'll work.

Note: we know that usually you'd use branches & forks to do this. But for some reason Github Pages only works on one branch and we'd like anyone to be able to see & code changes without installing things locally. This way, if you can vaguely code HTML you're a 1st class citizen in editing the site.

If you have edits to github docs (contributing, readme, support, code of conduct) etc they're best made in the other repo, as they'll be different here.

### Wait, how do you even write Do-a-thon?

* When presented with OpenCon, it's a "Do-A-Thon", an OpenCon Do-a-Thon in fact
* When presented an event type more generally, it's a do-a-thon.
* In URLs, or other places where adding dashes hurts UX, it's doathon

### Release instructions

* Copy files, or changes (once tested) over from Dev to live. On /doathon, the website files live under /docs. This means almost all your changes and files will be in that folder.
* There are some inconsistencies between dev & live to be aware of when moving things over. Here is what they are, and how to fix them:
  * Image links: On dev, these are usually structured /doathon-dev/images and on live they need to be just /images. You can check and do this in bulk but searching the directory for "/doathon-dev/images" (specifying all that is important!) and asking it to be replaced with "/images".
  * Links:
      * replace "index.html"" with ""/""
      * replace ""participate.html"" with ""/participate""
      * replace ""project.html"" with ""/project""
      * replace ""challenge.html"" with ""/challenge""

  * Github specific
    *  Only in the readme:
        * replace "https://sparcopen.github.io/doathon-dev" with http://doathon.opencon2017.org
        * replace ".html" with nothing.

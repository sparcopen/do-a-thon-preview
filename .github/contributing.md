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
  * Images: On dev, these are usually structured
  * Links
  * Github specfic

And, before you commit your code you can run the following quick checks to catch common errors:
 * search for https://sparcopen to find bad links
 *

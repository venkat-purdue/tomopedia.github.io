---
layout: page
title: Questions
permalink: questions/
include_in_menu: true
---

## How to contribute?

There are many ways to contribute to the Tomopedia website, and we encourage
everybody to do so. Most of Tomopedia's content is written in [Markdown](https://en.wikipedia.org/wiki/Markdown),
which makes it easy to edit content with any text processor.

Below is a list of possible ways of contributing, with some
guidelines on how to proceed.

#### Report errors
If you see an error on this website, or want to suggest something that can
be added by someone else, please open an issue on Tomopedia's github page [here](https://www.github.com/tomopedia/tomopedia.github.io/issues).

#### Edit files directly on GitHub
The easiest way to make small changes and additions to Tomopedia is to edit the
files directly on Tomopedia's [GitHub page](https://www.github.com/tomopedia/tomopedia.github.io/).
A tutorial on how to edit files on GitHub is provided [here](https://help.github.com/articles/editing-files-in-another-user-s-repository/).
Note that someone with administrator access to Tomopedia has to accept the changes
before they will show up on the website.

#### Propose changes in pull request
For bigger changes, it is better to [fork](https://help.github.com/articles/fork-a-repo/)
the Tomopedia [git repository](https://github.com/tomopedia/tomopedia.github.io),
make your changes, and create a [pull request](https://help.github.com/articles/creating-a-pull-request/).
Tomopedia runs on [GitHub pages](https://help.github.com/categories/github-pages-basics/) using [Jekyll](https://jekyllrb.com/),
and should not be difficult to edit. The main pages (those that show up in the menu)
are located in `main_pages/`, while specific pages about algorithms or software
packages are arranged by topic (e.g. TomoPy's page is located at `software/tomopy.md`).

#### Get direct access to git repository
If you expect to make regular additions or modifications to Tomopedia, it is
easier to get direct access to Tomopedia's git repository. To do so, please
create an issue on GitHub [here](https://www.github.com/tomopedia/tomopedia.github.io/issues)
with a request for access.

#### Timing algorithms/packages
When adding new software/algorithms, we recommend providing timing information for typical ~512^{3} , 1024^3 and ~2048^3 transmission tomography data sets from the databank [here](https://tomobank.readthedocs.io/en/latest/) and information on the hardware used to provide to run the software.  

# Help Guide for Vivaldi Wiki pages

## Overview

The guide aims to help you to understand how you can add contents to this project (Vivaldi Wiki) easily.
test

## Project Pages

The project is live on following web pages :

* **[Wiki Page](http://wiki.vivalditips.com/en/latest/)**
* **[Repository](https://github.com/vivalditurkiye/wiki)**

## How to Contribute to the Wiki?

### Required Things

* A Github account

  You should create [a new account](https://github.com/join) to create a new file or edit the actual one.

* Basic Markdown Knowledge

You should check [here](http://commonmark.org/help/) in order to learn basic commands.
Here's an example workflow for a project ``wiki`` hosted on Github, which
is currently in version 1.3.x. Your username is ``yourname`` and you're
submitting a basic bugfix. (This workflow only changes slightly if the project
is hosted at Bitbucket, self-hosted, or etc.)

### Preparing your Fork

1. Hit 'fork' on Github, creating e.g. ``yourname/wiki``.
2. Clone your project: ``git clone git@github.com:yourname/wiki``.
3. Create a branch: ``cd wiki; git checkout -b foo-the-bars 1.3``.

### Making your Changes

1. Add changelog entry crediting yourself.
2. Write tests expecting the correct/fixed functionality; make sure they fail.
3. Hack, hack, hack.
4. Run tests again, making sure they pass.
5. Commit your changes: ``git commit -m "Foo the bars"``

### Creating Pull Requests

1. Push your commit to get it back up to your fork: ``git push origin HEAD``
2. Visit Github, click handy "Pull request" button that it will make upon
   noticing your new branch.
3. In the description field, write down issue number (if submitting code fixing
   an existing issue) or describe the issue + your fix (if submitting a wholly
   new bugfix).
4. Hit 'submit'! And please be patient - the maintainers will get to you when
   they can.

### Create a new document

Open the main repo and create a new file:

* New file should be recorded as **.MD** file type.
* File name should be the same as the file URL , like;
  How to disable flash? / how-to-disable-flash
* All documents should be save under /Docs path

### Adding image

You can add many type of images into your file. Recommended file types are **.JPG** and **.PNG**. We do not recommend **.GIF** files as well.

* All images should be under **/Docs/Images** path


### In your locale language

* There are a few locale repository on Github. Go to the repository that is related with your language.
* Add a new page or edit something.
* Request a pull-request.

## Technologies

This project uses following systems.

* [Github](https://github.com)
* [Read the Docs](https://readthedocs.org/)
* [Markdown](http://commonmark.org/)

Documents are built for every commit in `master` branch. This build process takes approximately a minute.

_Note: This project is developed by **[VivaldiTips](http://vivalditips.com)** team and contributed by **Sopranos Team**._

# Quick Start Guide #

This tutorial will try to get **protoc-gen-docbook** up and running on your machine with as few steps as possible.

_This tutorial is for Windows user only. Tutorials on other OS's are in progress ([issue 1](https://code.google.com/p/protoc-gen-docbook/issues/detail?id=1))._

## Before we start ##
Download the latest release from the [Download](http://code.google.com/p/protoc-gen-docbook/downloads/list) page. You want the **Full Release** since it comes with everything you need.


## Step 1 - Unzip the release package ##

[Unzip](http://www.7-zip.org) the release, and you should see the following folder layout.

https://protoc-gen-docbook.googlecode.com/svn/wiki/images/tutorial/step01.PNG


## Step 2 - Put your protos in the deploy folder ##

Open up the **deploy** folder and put all your proto source files in this folder. Then click on **Run.bat**.

https://protoc-gen-docbook.googlecode.com/svn/wiki/images/tutorial/step02.PNG


## Step 3 - Wait... ##

At this point, a command prompt should pop up with some messages and warnings (don't worry, they are harmless). This is Apache FOP performing its PDF transformation. Depending on your proto files, it may take a few seconds or more.

https://protoc-gen-docbook.googlecode.com/svn/wiki/images/tutorial/step03.PNG

## Step 4 - Profit ##
Now you should see two new files generated by the transformation. **docbook-out.xml** is the DocBook output, and **docbook-out.pdf** is the PDF output. That's it!

https://protoc-gen-docbook.googlecode.com/svn/wiki/images/tutorial/step04.PNG

## More Information ##
See [docbook.properties](docbookProperties.md) definition for more configuration options.

See [Custom Template Guide](CustomTemplateGuide.md) for tutorial on how to inject DocBook tables into preexisting DocBook document.
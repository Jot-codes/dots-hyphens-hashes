---
layout: default
---

# Creating GitHub Pages for Dummies

You would like to have a web page and you want to set it by yourself but you don't know where to start with. This tutorial presents how to create a simple web page based on free templates. You can store and maintain your web page for free on GitHub Pages.

## Prerequisites
Make sure that you have an account on GitHub, GitBash installed. If you don't know how to do this, check next sections.

### Creating an Account on GitHub
To work with GitHub you need to create an account on GitHub.
Go to [https://github.com/](https://github.com/), click _Sign_ _in_ button and provide all required data.

### Downloading Git
To make your GitHub pages run and to maintain them, you need a tool called Git. Navigate to [https://git-scm.com/downloads](https://git-scm.com/downloads) to download and install the tool.

### Choosing a Template
Since you don't create the whole web page from scratch, you need to choose a template, which you want to use. Choose one from listed here: [https://pages.github.com/themes] (https://pages.github.com/themes).
Just choose the design you like. You don't have to do anything more, yet ;)

## Placing the Template on Your GitHub


### Downloading the Template to Your Local Machine

1. On your local machine, navigate to a directory, where you want to keep the Template.
1.Open the Template page on repository on GitHub.
1. Click _Clone_ _or_ _Download_ button and copy a URL.
1. Open GitBash in the directory, where you want to keep the Template.
1. Run
```
git clone URL_to_your_template
```
for example:
```
git clone https://github.com/pages-themes/cayman.git
```
Your template is available for your needs locally.
1. Do not close the GitBash window.

### Personalizing Your Main Page
The main page is a place where you want to welcome your visitors and put and information about the page. The main page content is stored in the _index.md_ file.
1. On your local machine, edit the _index.md_ file.
1. Copy a content of the file to any new _.txt_ file.
As you can see, the _index.md_ file provides information about page formatting and that's something that you will need to format your pages.
1. Go to _index.md_ and delete all the content below:
```
---
layout: default
---
```
1. Place your content. For example:

***
```
# Welcome to My Place!
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse orci nulla, pellentesque vel posuere ac, maximus vitae orci. Morbi congue eu felis feugiat sodales. Sed rhoncus rutrum nibh. Proin sagittis nulla a euismod lacinia. Mauris porta rhoncus semper. Donec tortor erat, luctus ut ornare quis, varius nec justo. Sed non porta odio, quis tincidunt ligula. Nullam semper vitae augue et varius. Quisque sapien lorem, tristique eu diam vel, varius dapibus massa.

## Who Am I?
Praesent volutpat leo cursus lacus tempus, ut sagittis nisi ullamcorper. Cras elementum sem sapien, non feugiat nibh posuere at. Etiam interdum nisi velit, eu pulvinar risus dictum nec. Fusce luctus metus eget urna ultricies hendrerit. Nullam eu erat mattis, consequat justo sit amet, commodo dui. Phasellus fermentum mauris non iaculis ultricies
## What Is this Site About?
Aenean in odio turpis. Fusce auctor sapien arcu, id consequat tortor malesuada nec. Mauris finibus urna eu neque sagittis consectetur. Aliquam iaculis accumsan semper. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Sed rhoncus commodo lorem, id elementum sem ullamcorper eget. Praesent magna massa, tincidunt id ante quis, tincidunt sagittis velit.
```
***
1. Save the file.

### Uploading Your Page to Your Repository on GitHub

1. On you GitHub account 
1. In GitBash window, run 
---
layout: default
---
```
1.
1.



[back](./)

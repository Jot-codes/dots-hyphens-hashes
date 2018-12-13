---
layout: default
---

# Creating GitHub Pages for Dummies

You would like to have a web page and you want to set it by yourself but you don't know where to start with. This tutorial presents how to create a simple web page based on free templates. You can store and maintain your web page for free on GitHub Pages.

## Prerequisites
Make sure that you have an account on GitHub and Git installed. If you don't and you don't know how to do this, check the next sections.

### Creating an Account on GitHub
To create a repository on GitHub you need to create an account on GitHub.
Go to [https://github.com/](https://github.com/), click _Sign_ _in_ button and provide all required data.

### Downloading Git
To manage your GitHub pages and to maintain them, you need a tool called Git. Navigate to [https://git-scm.com/downloads](https://git-scm.com/downloads) to download and install the tool.

### Choosing a Template
Since you don't create the whole web page from scratch, you need to choose a template, which you want to use. Choose one from listed here: [https://pages.github.com/themes] (https://pages.github.com/themes).
Just choose the design you like. You don't have to do anything more, yet ;)

## Placing the Template on Your GitHub Repository

### Downloading the Template to Your Local Machine

1. Open the Template page of your choose on GitHub.
2. Click _Clone_ _or_ _Download_ button and copy a URL.
3. Open GitBash in the directory, where you want to keep the Template.
On Windows machines: Right click inside the folder -> Git Bash Here
4. Run
  ```
  git clone URL_to_your_template
  ```
for example:
   ```
  git clone https://github.com/pages-themes/cayman.git
  ```
Your template is available for your needs locally.

5. Do not close the GitBash terminal window.

### Personalizing Your Main Page
The main page is a place where you want to welcome your visitors and put and information about the page. The main page content is stored in the _index.md_ file.
1. On your local machine, edit the _index.md_ file with the text editor of your choose.
2. Copy a content of the file to any new _.txt_ file.
As you can see, the _index.md_ file provides information about page formatting and that's something that you will need to format your future pages.
3. Go to _index.md_ and delete all the content below:
```
---
layout: default
---
```
4. Place your content. For example:

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
5. Save the file.

### Uploading Your Page to Your Repository on GitHub
Copy the changes made locally to remote repository.
1. On GitHub page, click + button next to your profile's icon and select _New_ _repository_.
2. In _Repository name_ field, provide the name of your repository.
For example: cayman.
Your repository is created. In _Quick setup — if you’ve done this kind of thing before_ section, you can find URL to your just created repository, referred as <url> in next steps.
3. Switch to GitBash terminal.
4. Run 
```
git add index.md
```
to add the _index.md_ file contents to the index.
  
5. Next, run
```
git commit -m "your comment"
```
to record changes to the repository with a comment what was changed.

6. Add your remote repository for the repository at <url>
```
git remote add name_of_your_repository <url>
```
for example:
```
git remote cayman https://github.com/Justyna1Adam/cayman.git
```
7. Push local updates to your remote repository:
 ```
 git push -u name_of_your_remote_repository master
```
for example:
 ```
 git push -u cayman master
```
Your page is updated.
## Viewing Your Page
1. On Git Hub page, go to your repository.
2. Select _Settings_ tab.
3. In GitHub Pages section, select _master branch_ for Source and save changes.
  You get the following information above the GitHub Pages section:
  ```
  Your site is ready to be published at <url_to_your_page>.
  ```
4. Click the URL and enjoy your first page on GitHub Pages.

[back](./)

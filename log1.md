# Log: Week One

## Newcomer Sequence

1. __Markdown Using Atom__
- When I first saw the cheatsheet of markdown, I was a little intimidated and couldn't understand **why** we would take the time to use it. _Just another thing to try to memorize._ Embarrassingly, I didn't realize that I don't need to put the underscores or asterisks between every word in a sentence that I wanted to _italics_ or **bold** until I saw an example of **Nicholas Surges** work. So, thank you **Nicholas** for making my life a million times easier!
However, after writing the tutorial paragraph, it became less intimidating and actually easier to use than it word. Although, I'm still unsure if my pictures and website will be embedded properly.
  - I Just learnt that I can preview my markdowns in Atom by going to __packages__, down to __markdown preview__, and selecting __toggle preview__.
  - My website link did not work at first. I wasn't sure what had gone wrong here, so I recopied the link and pasted it. That still did not work. _However,_ I realized that when I pasted the link, it was spaced apart in an area. Deleting the space connected the link and now it works.

2.  __Github__
- Honestly, not really sure I understand what I am doing. However, no issues with creating an account and repository.
  - I selected "_create a new repository_", named it _week-one_, made sure it was on public, and selected "_initialize this repository with a README_", clicked "_create repository_". I was brought to a new page which shows my repository, I went to "_settings_", "_manage access_" and "_invite collaborator_". I invited Dr. Graham, through his user name _shawngraham_. I did this for my other three assignments as well.
- I used the "_upload file_" and "_drag and drop_"
- Did not have any issues with using Github.
- _However,_ I believe that my photos come up a little strange, when Uploaded to Github.

- __SO I did run into some issues__ with my images not showing up after uploading these files to _Github_. I had to go back to the class website and rewatch Dr. Graham's video tutorial "_Uploading a file on Github_". I rewatched it several times, not really understanding my issue. Then I realized that the file he uploaded in the video was the image. So here are the steps for how to get images to show up on Github:
 1. Under your repository, select _"Upload file"_, I chose to use the drag and drop method, but you can also upload from computer.
 2. Upload all photos used in repository (log, reflection, tutorial, etc.) Or simply, upload the entire file of work (which is what I should have done, but didn't understand at first)
 3. Select submit changes. Then there are two options:
     1.  If your log/ reflection already has the photos embedded, (in which case you should check if the images are there now) you shouldn't have to do anything further.
     2.  *However*, you can also embed them now, example: ![image name] (imagefile) (without the space between the 2 sets of brackets and add the .png or .jpg to the imagefile.
     3.  **MAKE SURE TO DOUBLE CHECK IMAGES** a couple of mine still didn't work after uploading, so I had to re-due the tag.



3. __Anaconda__
- So this is where everything went downhill for me. **Real quick.** For whatever reason (Probably because my computer is old and slow) trying to download anaconda just was not happening for me. (The only option I had for download was _Python 3.8 64-Bit Graphical Installer (440 MB)_ for macOS)
  - First froze my laptop. I had to wait for it to die, charge and then try again.
  - Second time trying, I got through the prompts and then got the message of "_The Installation failed_" ![screen shot](screenshot.png)
  - So, I deleted anaconda from my laptop and tried again. Following the exact steps outlined [here](https://docs.anaconda.com/anaconda/install/mac-os/) for installing anaconda to macOS. Which is basically following the prompts, until you get to the "_select destination_", it automatically has chosen "_for me only_" but says "_cannot installed in this location_", you click the "_for me only_" **again** and it should work. I did this at the recommendation/ instruction of the website's tutorial. It said that installing the program else where is not recommended.<sup>1</sup>
  - Third time around it downloaded, got through all the prompts without an issue. __HOWEVER__, none of the of the applications within the anaconda would launch. I would click on _RStudio_ and the loading bar would say "_launching RStudio_" but nothing would happen.
  - I tried restarting the app, then restarting my laptop and *__nothing__*. My laptop froze again.

      - Did reach out to a friend who is in his fourth year of computer science at Carleton for some insight on my issues. (Felt more comfortable asking a friend, since my assignment was late.) He also uses macOS. He wasn't sure what was happening when I showed him through FaceTime.
      - Tried to delete some old files and apps that I no longer use to free up some space, since Anaconda is a large file.
      - My friend downloaded Anaconda to see if he would have issues, following the guide that I did online (basically just following the prompts and re-clicking "_install for me only_" as the guide suggests.) It worked fine for him. So, I do believe that the issues I am having is due to having an older generation. _Though I could be wrong, I really don't know much about computers_.

- I gave up on my laptop, had to wait to borrow my boyfriend's laptop on Monday, May 17. 4 days after this assignment is due.
  - Now using a windows laptop. (Which I'm pretty lost on, I have only used Mac systems for the past 6 years. But, I am hopeful.)
  - Downloaded _Python 3.8, 64-Bit Graphical Installer (477 MB)_ for Windows. Made it through all the prompts without any issue, seems to have downloaded properly.
  - Now installing _Powershell Prompt._ Took awhile to install/ launch. But so far so good. To make sure everything is installed, I typed in "_conda --version_" got "_conda 4.10.1_" in return, next typed "_python --version_" got "_python 3.6.13 :: Anaconda, Inc_" in return. So things are looking up!
  - Following prompts from **Navigating the Commandline**: Not sure if if this is an issue, ![SS3](SS3.jpeg) but other than that everything seems to be working.

  4. **Cleaning & Manipulating Data with R:**
  - Just a side note: _The Survey of Scottish Witchcraft_ sounds super interesting, will have to go back a more thorough read!

  - *__Moment of truth:__* Installing _RStudio._
      - A new error has arisen
      ![screen shot 2](screenshot2.jpg)
      - Selected "_create_", not really sure what this did, however, RStudio now works!
  - Opened _RStudio,_ typing in "_install.packages("tidyverse")_", and then "_install.packages("tidy text")_" I don't believe there was any issues, a lot of code came up. The last few lines all say "successfully unpacked". So that is a good sign.
  - Next, I typed in "_library(tidyverse)._" It came up with a **warning message** "packages(s) built under R version 3.6.3".
  - "_library(magrittr)_" and _"library("tidytext")"_ came with the same **warning messages.**
    - Checked the discord group, and it seems that the "_built under R version 3.6.3_" doesn't matter. So that is a relief.


  - **Loading your data** ran in to many, many, many problems here.
      1. The instructions say to _right-click and save as to the folder where you're working with R OR copy the url and change the cold below appropriately._ (code being '_read_csv_' or '_read_url_') __However__ did not specify that when you're saving to the folder, to _save as_ fairy-elements.**csv**. I could not understand why it wasn't working for me, it just kept coming up with error codes, the _url_ path was not working for me either. So, **desperately** I tried saving the website as with **.csv** and it worked. Kind of.
      2. So after trying the "fairyElements <- read_csv("fairy-elements.csv")" every way imaginable, I finally got something. __BUT__ it was a bunch of error codes basically. ![screen shot 5](screenshot5.png)

- **Finally,** I decided that it was time to ask for help. (**Note to self: ask for help sooner next time.**) And here is what I found out:

- **Where I went wrong:**
  1. I was not supposed to be doing the tutorial for "Cleaning & Manipulating Data with R". The tutorial shows up between the "_Anaconda_" and the "_excel & into to R_" tutorials. So I made the assumption that the tutorial would be tacked on to **Part 1**. Now that I think about it, that doesn't even make sense, considering int **Part 2** we have the *__intro to R__*. So my panic and confusion and lateness of this assignment could have all been avoided if I had just reached out and asked for clarification. I have a tendency to over complicate things for my self.
  2. **Where I went wrong in the tutorial** *__however,__* is that I was writing/ working in the _console_ of R, rather than writing a _script_. Which looking ahead to __Part 2__, makes sense/ is explained.

---
Work cited

<sup>1</sup> "Installing on MacOS." Anaconda Documentation
https://docs.anaconda.com/anaconda/install/mac-os/

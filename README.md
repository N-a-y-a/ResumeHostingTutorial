# Hosting a Resume

## Purpose
The steps below describe how I hosted [my resume](https://n-a-y-a.github.io/ResumeHostingTutorial) on GitHub Pages, and how you can do the same. I also describe the general principles of current Technical Writing, as explained in Andrew Etter's book *Modern Technical Writing*.
<br><br>

## Prerequisites 
Before hosting your resume on GitHub Pages, you need to have a Markdown-formatted resume! If you are unfamiliar with Markdown, please see the **More Resources** section for helpful links.

You must also have a GitHub account. It is easy to make one and you can do so [here](https://github.com/).
<br><br>

## Instructions

### Create a Repository
GitHub is a form of distributed version control, which is something Etter promotes the use of in his book. Within GitHub, the code repository is where your resume will be stored, like a folder on a computer. To create the respository, follow these steps:

1) Log into GitHub.
2) On the right-hand side, locate the section that says **Start a new repository for username** (where username is replaced with your GitHub username).
3) For your repository name, type username.github.io (where username is again replaced with your real GitHub username). The name is *very* important, so double check that you have spelled everything correctly.
4) Click **Public** so that others will be able to see your resume.
5) Click **Create a new repository**.
<br><br>

### Upload Your Resume
For this section, you will need your Markdown-formatted resume ready. 

1) In the blue text-box on your screen, click **uploading an existing file**.
2) Drag and drop your file onto this screen.
3) Underneath the header **Commit changes**, there are two text boxes. The first textbox is the kind of action you are taking (ie. uploading a file) and the second is further description of the action. Write a short message in second text box (ie. 'Uploaded my resume').
4) Click **Commit changes**.

As you continue to commit changes, GitHub will track them. This reflects Etter's principle of catalogging the diff. In other words, GitHub is keeping a change log of your resume for you. Keeping your commit messages concise will allow you to scan through them quickly if you want to look through the history. 
<br><br>


### Rename Your Resume

If you are like me, your resume file was likely named something like 'resume.md'. To host your resume on GitHub pages, it has to be called 'index.md'. To change it:

1) Click on your resume file name.
2) Click on the pencil icon on the right-hand side to edit the file.
3) Change the name of the file in the textbox to 'index.md'. The spelling is very important.
4) Click **Commit changes...**.
5) Add a description to your commit message to say that you have changed the name of your resume.
6) Click **Commit changes**.

Any time you want to edit or create a file, you'll be shown the same screen and you can follow the same process.
<br><br>


### Look at Your Resume

At this point, you should be able to see your resume on GitHub Pages. To access it:

1) In a new tab, navigate to username.github.io. 
2) Your resume should be displayed. If not, wait a couple of minutes (it can take some time to deploy). If it still isn't displaying, see the **FAQs** section.

Etter identifies building a website/making static websits as principles of technical writing. Having your resume hosted ensures that everybody who looks at it is seeing the most recent copy and there is no risk of sharing an old version accidently. It also encourages you to keep it up to date and allows you to update or correct it quickly, even after it has been shared.
<br><br>


### Add a Configuration File

If you are satisfied with the way your resume looks, you can stop here. However, I used a theme to make my resume more aesthetic and I recommend that you do too:

1) Navigate to the main page of your repository (click **Code** in the top left-hand corner). 
2) Create a new file by click the **+** button located beside the green **Code** button and selecting **Create new file**.
3) Name the file _config.yml.
4) In the body of the file, type 'remote_theme: pages-themes/slate@v0.2.0'.
5) Commit the change.
6) Refresh your other tab to see the change (you may need to wait a couple minutes).

You have now elevated your static site by using a theme to add some colour and apply a more interesting format. It should look something like this:

![resume-gif](https://github.com/N-a-y-a/N-a-y-a.github.io/blob/main/resumeGif.gif)
<br><br>


### Edit/Maintain your Documentation

All that's left is to edit and maintain your files. I added more line breaks to my resume to improve spacing. I also changed the title and added a description in the configuration file (see the slate theme documentation for instructions). You may also want to experiment with different themes (see  **More Resources**).

You can also edit your resume to apply Etter's principles. Consider who will be looking at your resume and confirm that the vocabulary and level of detail is appropriate. Additionally, you can add headers and tables as appropriate and confirm you are using any acronyms consistently to ensure good style. 

One final tip is to publish frequently, as Etter encourages technical writers to do. It is important to keep your resume up to date as you gain experience.
<br><br>


## More Resources
* If you are unfamiliar with Markdown and would like to learn, try [this tutorial](https://www.markdowntutorial.com/) or [this one by Davarshi Shimpi](https://dev.to/devarshishimpi/complete-markdown-tutorial-for-beginners-1e#:~:text=Complete%20Markdown%20Tutorial%20for%20Beginners%201%201.%20Structuring,Separating%20Sections%20with%20Horizontal%20Lines%20...%20More%20items).
* This [Cheat Sheet by Adam Pritchard](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is good as a refresher.
* To see what your Markdown-formatted resume looks like before hosting it on GitHub Pages and without downloading any software, [Dillinger](https://dillinger.io/) is a great resource. 
* If you are interested in learning more about that themes that GitHub Pages support and how to implement them, see [this documentation](https://pages.github.com/themes/).
* An e-copy of Andrew Etter's book *Modern Technical Writing* can be purchased on [Amazon](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
<br><br>

## Authors and Acknowledgements
For my resume, I used the [Slate theme](https://github.com/pages-themes/slate?tab=readme-ov-file). You can find the documentation and a list of contributors in the repository.

Many of the concepts discussed and implemented in this project come from Andrew Etter's book *Modern Technical Writing*, and a link to purchase the e-book is included in the **More Resources** section. 

I would also like to say thank you to my group members (whose names will not be mentioned for privacy reasons) for their peer review.
<br><br>

## FAQs

### Why is my resume not showing up?
If you navigate to username.github.io and it shows a 404 error, see this [troubleshooting documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-404-errors-for-github-pages-sites) for help. Please note that index.html in this documentation should be replaced with index.md for your purposes.

### I like using my word processor. Why should I use Markdown instead?
There are many reasons why Markdown may be a better choice than your word processor. This [article by Nikita Dhulekar](https://www.makeuseof.com/why-is-markdown-popular-reasons-you-should-use-it/#:~:text=Why%20Is%20Markdown%20So%20Popular%3F%207%20Reasons%20You,7%207.%20Converting%20Content%20to%20Markdown%20Format%20) discusses many of those reasons.

# GitHub

Here is a series of guidelines and exercices to help you get started with GitHub. A few things to keep in mind:

- GitHub is a skill with a steep learning curve (one of the steepest in my opinion). But it is absolutely worth to put the effort in (there's a reason it's one of the most popular and fastest-growing platform)
- GitHub has a confusing language: pushing, pulling, forking, cloning, committing, ...
- GitHub can be interacted with in many ways. Don't be fooled by internet comments though, we **don't need to use the console with command lines** ever. In fact, we use the amazing [**GitHub Desktop**](https://desktop.github.com/) 
- GitHub can only be mastered via trial and error, by trying to use it again and again. And once it "clicks", it becomes second nature. All you need is perseverance!

## Download a GitHub repository locally on your computer

You can download any repository on your computer by clicking the green button and downloading it as a **zipped** folder. Once it is saved on your computer (e.g., in the `Downloads` folder), you will need to unzip it by opening it, and dragging the content from the zip to a folder on your computer.

![](img/GH_download.png)


## Create your own first repo

Now, create your first repository! You can leave it mostly empty for now, it's just an experiment ground :relaxed: We recommend starting with a README page that will serve as your profile page. 
Importantly, **take some time to play around**; create repos, delete them, try to add things etc. The more time you spend getting familiar with the website the easier the next steps will be.

- **To Read**: [Creating and customizing your profile README page](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme
)

## Download GitHub Desktop

The easiest way to interact with GitHub from your computer is via [**GitHub Desktop**](https://desktop.github.com/). Download, install, and log in. 
This app essentially makes accessible your repositories as regular folder on your computer.

- Try to clone (i.e., download) a repo that you created in the previous step
- Once you have the repo on your computer, try adding a file to it (an empty text file). Then, from GitHub desktop, try to "commit" and "push" this change.
- Your new file should now also show on its online page (meaning it has successfully been "synced" between your computer's folder and the GitHub website)

## Create your first Github Pull Requests (PR)

As said earlier, **we use GitHub a lot**, so it's key that you acquire this complicated skill. However, it's quite tricky to get familiar and comfortable with it, and I'd say it's one of the most complicated things you'll have to learn. But you cannot learn if you don't try, break things and succeed.

- **Make a PR in this document here**

The first task is to create a Pull Request (PR) to modify *this very page*. Go to the [README page](https://github.com/RealityBending/Onboarding/blob/master/README.md) file and hit the "Fork and edit" button (the pen icon at the top right corner). Under the hood, this will create a fork of the Onboarding account under your repo. You can then edit the file. **Add *your* profile to the "Edited by" section at the bottom of this page**. Then, propose the change and see what happens.

- **To Read**: [markdown introduction](https://guides.github.com/activities/hello-world/)


## Setting up your profile on the REBEL website

The next task is to set up your profile on the [lab website](https://realitybending.github.io/people/).

- **Step 1: Fork the website repository**
    - Go to the [Github Repository of website](https://github.com/RealityBending/RealityBending.github.io)
    - Hit the **fork** button at the top right corner to make a *copy* of the repository in your Github account.
    - After a few minutes of waiting, you should now see a repository with a name like `your-username/RealityBending.github.io`.

- **Step 2: Understand how a profile is made**
    - In your newly *copied* repository, navigate to the folder `your-username/RealityBending.github.io/content`. This is where all the content of the website is stored.
    - Click on the `authors` folder. As you can see, each member has a folder (in lower case with a hyphen instead of spaces).
    - Explore one of these folders, for instance Gandalf's. It includes two files, *_index.md* file (The extension *.md* stands for **markdown**) and an image file named `avatar`.
    - Click on the .md file, and then on the **raw** button (on the right) to see the raw file (as a notepad would see).
    - The index file contains all the information, and is organized into a YAML header (delimited by 3 dashes ---) and then some text.


- **Step 3: Add your profile to the website**

    - Now that you understood how a profile is made, create on your computer a folder named `firstname-surname` (replace accordingly).
    - In this folder, put your profile pic and name it `avatar`.
    - Create a new text file named `_index` and replace the extension so that it's `.md` instead of `.txt` (google how to see file extensions if you're on windows and don't have it activated).
    - Open it with any raw text editor like notebook or RStudio or VScode (but not Word!).
    - Replace the text for something that applies to you.

- **Step 4: Commit to your fork**

    - On the `your-username/RealityBending.github.io/contentauthors/` page, you should click on **Add file** (on the right) and then **Upload files**.
    - Drag and drop your folder and click **"commit"**. You can add a commit message such as "Added my profile"/
    - You should see the folder that you just created at `https://github.com/your-username/RealityBending.github.io/tree/main/content/authors/MY-NEW-FOLDER`

- **Step 5: Make a Pull Request**

    - Great, you added the files to your own copy of the website. But now we need to merge these changes into the **original** repository.
    - Look for the *Pull Rquest* sign. Click on it.
    - The page will show that you are trying to make a Pull Request from **your** repository *"your-username/RealityBending.github.io"* to the **original** repository *RealityBending/RealityBending.github.io"*.
    - All the left for you to do is to click on that shiny green button to create the pull request (PR). Your profile will appear on the website as soon as an administrator validates the PR.

Congratulations! You have successfully updated your profile on our website!

Note that on GitHub (but also when writing research articles), we write in **markdown**, which is a set of conventions allowing to quickly and easily format text (e.g., text in bold, italic, titles, etc.).

- [**To read: markdown introduction**](https://guides.github.com/features/mastering-markdown/)


Further reading.

- [How to use Github to contribue](https://neurokit2.readthedocs.io/en/latest/contributing/contributing.html#how-to-use-github-to-contribute)
- [How to create a Pull Request](https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/github-collaboration/how-to-submit-pull-requests-on-github/)
- [Github Cheatsheet](https://github.com/tiimgreen/github-cheat-sheet)
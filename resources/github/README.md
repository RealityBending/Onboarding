# GitHub

After you created an account and opened your first issue (as instructed [**here**](https://github.com/RealityBending/Onboarding?tab=readme-ov-file#octocat-github)), here is a series of follow-up exercises to help you get started with GitHub. A few things to keep in mind:

- GitHub is a skill with a steep learning curve (one of the steepest in my opinion). But it is absolutely worth putting the effort in (there's a reason it's one of the most popular and fastest-growing platforms)
- GitHub has a confusing language: pushing, pulling, forking, cloning, committing, ... It just needs to get used to it.
- GitHub can be interacted with in many ways. Don't be fooled by internet comments though, we **don't need to use the console with command lines** ever. Instead, we use the amazing [**GitHub Desktop**](https://desktop.github.com/) 
- GitHub can only be mastered via trial and error, by trying to use it again and again. And once it "clicks", it becomes second nature. All you need is perseverance!

## Concepts 

An important distinction to have in mind is between what's **local** (i.e., saved on the hard drive in a folder on your laptop) and **"on GitHub"** (on the GitHub *"cloud"*: we can see it on the *website* GitHub.com).

You  might have files saved **locally** that are also synced via a cloud platform like Google Drive, OneDrive, Dropbox or Box: these folders are **automatically** synced every time you modify them. That is **not** the case for GitHub: although there is a "link" between a local folder and a repository on GitHub, we must **manually** sync it. Moreover, you can have a folder synced between your laptops on Dropbox, that is also linked to a GitHub repository: the two things are independent. 

**There are different ways of interacting with GitHub**. Let's start with the simplest.

## Exercise 1: Download a GitHub repository locally on your computer

You can download any repository on your computer by clicking the green button and downloading it as a **zipped** folder. Once it is saved on your computer (e.g., in the `Downloads` folder), you will need to unzip it by opening it, and dragging the content from the zip to a folder on your computer.

![](img/GH_download.png)

*Note*: You can also download individual files with the "download" icon. 

- Exercise: Download the [**Onboarding**](https://github.com/RealityBending/Onboarding) repo locally, find the file you're reading now (in `resources/github/README.md`) and open it using a notepad or VScode. 


## Exercise 2: Create your first repo

Now, create your first repository! You can leave it mostly empty for now, it's just an experiment ground :relaxed: We recommend starting with a README page that will serve as your profile page. 
Importantly, **take some time to play around**; create repos, delete them, try to add things etc. The more time you spend getting familiar with the website the easier the next steps will be.

- **To Read**: [Creating and customizing your profile README page](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)


## Exercise 3: Download GitHub Desktop

The easiest way to interact with GitHub from your computer is via [**GitHub Desktop**](https://desktop.github.com/). Download, install, and log in. 
This app essentially makes accessible your repositories as regular folders locally on your computer.

- Try to clone (i.e., download) a repo that you created in the previous step in a folder on your computer (for instance, you can make a folder for `Research/` where you will put all the repositories that you will be using) 
- Once you have the repo on your computer (e.g., your "profile" repo that you created in the previous exercise), try adding a file to it (a text file or an image). Then, from GitHub desktop, try to "commit" and "push" this change.
- Your new file should now also show on its online page (meaning it has successfully been "synced" between your computer's folder and the GitHub website)

## Exercise 4: Create your first Github Pull Requests (PR)

As said earlier, **we use GitHub a lot**, so it's key that you acquire this complicated skill. However, it's quite tricky to get familiar and comfortable with it, and I'd say it's one of the most complicated things you'll have to learn. But you cannot learn if you don't try, break things and succeed.

- **Make a PR in this document here**

The first task is to create a Pull Request (PR) to modify *the Onboarding page*. Go to the [README page](https://github.com/RealityBending/Onboarding/blob/master/README.md) file and hit the "Fork and edit" button (the pen icon at the top right corner). Under the hood, this will create a ***fork*** (a copy) of the Onboarding account under your repo. You can then edit the file. **Add *your* GitHub profile to the "Edited by" section at the bottom of this page**. Then, propose the change and see what happens.

- **To Read**: [markdown introduction](https://guides.github.com/activities/hello-world/)


## Exercise 5: Setting up your profile on the REBEL website

The final task is to set up your profile on the [lab website](https://realitybending.github.io/people/).

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
    - Replace the text with something that applies to you.

- **Step 4: Commit to your fork**

    - On the `your-username/RealityBending.github.io/contentauthors/` page, you should click on **Add file** (on the right) and then **Upload files**.
    - Drag and drop your folder and click **"commit"**. You can add a commit message such as "Added my profile"/
    - You should see the folder that you just created at `https://github.com/your-username/RealityBending.github.io/tree/main/content/authors/MY-NEW-FOLDER`

- **Step 5: Make a Pull Request**

    - Great, you added the files to your own copy of the website. But now we need to merge these changes into the **original** repository.
    - Look for the *Pull Rquest* sign. Click on it.
    - The page will show that you are trying to make a Pull Request from **your** repository *"your-username/RealityBending.github.io"* to the **original** repository *RealityBending/RealityBending.github.io"*.
    - The remaining thing for you to do is to click on that shiny green button to create the pull request (PR). Your profile will appear on the website as soon as an administrator validates the PR.

Congratulations! You have successfully updated your profile on our website!

Note that on GitHub (but also when writing research articles), we write in **markdown**, which is a set of conventions allowing to quickly and easily format text (e.g., text in bold, italic, titles, etc.).

- [**To read: markdown introduction**](https://guides.github.com/features/mastering-markdown/)


Further reading.

- [Official GitHub walkthrough](https://docs.github.com/en/get-started/start-your-journey)
- [How to create a Pull Request](https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/github-collaboration/how-to-submit-pull-requests-on-github/)

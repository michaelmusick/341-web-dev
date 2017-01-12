# GitHub.com

## Repository Hosting
[GitHub.com][1] is a web-based Git repository hosting service.

<iframe src="https://www.youtube.com/embed/VUaBfYCmJls" frameborder="0" allowfullscreen></iframe>

GitHub allows users to have an unlimited number of *public* repositories under 2GB each. Meaning your source code is publicly available to the world for them to view and fork (copy). This is great, as it encourages “[open source][2]” software projects. Open source software encourages the development of shared knowledge and progress within the open source community. It also means that all code is publicly viewable.

## Advanced Collaboration Tools
As you saw in the above video, GitHub also provides advanced collaboration tools. This is not something you will use much this semester. However, it is important to know about and you will use it in future projects.

## Static Website Hosting
GitHub also provides a service known as GitHub pages. This service provides free static website hosting. This is what you will primarily use this semester to host your web projects. (Did I mention it is free! This means you do not have to purchase server providers from another company.)

## Community Wiki Pages
Each repository also contains a community-editable wiki page, which can provide in depth information and how-to tutorials on a specific project.

## Issue Tracker
The Issues tracker serves as a place for people to create new “issue” or “feature requests”. This can then be used to assign people to work on these issues, ask for help from other users, or track the progress of a new feature.

# GitHub and This Course
This course, the one you are looking at right now, is being provided to you entirely through GitHub.

The website you are looking at now is hosted via GitHub pages.

Also, almost all of the resources for this course that you will need are available from a course repo. Eventually, I will show you how to “clone” the course repo to your own machine so that you can have easy access to these resources.

You will submit links to your homework assignments to the wiki page for the course repo. This will allow you to see each others work as well.

The wiki will also be somewhere that you can post resources

Finally, you will be expected to log “issues” which might be problems or questions. You will also be expected to respond to at least one issue every week.


# Getting Up & Running with GitHub

## Step 1 - Create an Account
First, visit [GitHub.com][3] and create a new user account.

**NOTE:** Please choose a username that you are comfortable with being part of your publicly visible URL. Ideally, this should be your name or something similar. Your username will be publicly available and used often for many things throughout this course and your entire time on GitHub.
![GitHub.com signup page][image-1]

- Fix any problems the signup engine informs you about.
- On Step 2: Keep “Unlimited public repositories for free.” selected. Then select “Continue”.
- Finally, go to the mail account you used during account creation and verify your e-mail address. 
- After your account is created, select the avatar in the upper-right hand corner. This should produce a dropdown menu. From there select the “Settings” option.
![GitHub Profile Setup][image-2]
- From here feel free to fill in as much or little of the public profile information as you want. (Although filling in your name and Profile Pic is encouraged)

## Step 2 - Link GitHub to SourceTree
After creating a GitHub account, the next step is to link it to SourceTree (or the GitHub Desktop App).

- In SourceTree, open preferences (cmd + ,) and navigate to the “Accounts” tab. 
- Click the “Add…” button.
- Under the “Host:” dropdown menu, select GitHub.
![GitHub Setup in SourceTree.app][image-3]
- Under “Username:” select the “Connect Account” button. Sign in to your GitHub account, using the credentials you just created.
![GitHub Login via SourceTree.app][image-4]
- You may then see another screen which you need to scroll down until you see a green “Authorize application” button, then click that button. (You may also skip this step depending on how GitHub views your computer)
![GitHub Authorization in SourceTree.app][image-5]
- Next, under “Protocol: “ change the dropdown menu from SSH to HTTPS.
![GitHub Authorization in SourceTree.app][image-6]
- Finally, click “OK”.
- You can now close preferences. 

## Step 3 - Add the Git Repo to GitHub.com
Finally, lets add our “341-work” Git repo to GitHub.com.

- Go to the Repository Browser window in the SourceTree app. (You can get to this from the “Window” tab in the menu bar.
- Right-click, two-finger-click, or control-click the 341-work repo to bring up the context menu. 
- Select “Publish to Remote…”
![SourceTree Remote repo setup][image-7]
- Make sure the Account and Owner are you.
- Leave the name of the repo at 341-work
- Make sure type is “Git”
- UNCHECK, the “This is a private repository” box.
- Then click the “Create” button.
- ![Git Repo Settings][image-8]
- After the repo is created remotely, you should see a window that starts with “Push to repository: “. This is how we sync data between a local git repo and a remote repo. 
- Select the “master” branch check box. 
- Then click “OK”
![Push repo to GitHub][image-9]

**NOTE: ** If you have “permission” problems do the following. 
- Go to GitHub.com, and select the 341-work repository, which should have been created.
![Push repo to GitHub][image-10]
- Select and copy the HTTPS address for the repo (as opposed to the SSH address).
![Push repo to GitHub][image-11]
- From the repo window in SourceTree, select the “Settings” button in the top-right hand corner, and then select the “Remotes” tab.
![Push repo to GitHub][image-12]
- Select the “origin” remote and click “Edit”.
- Replace the “URL / path:” address that starts with “git@github” with the “https” address you copied from GitHub.com. Then click “OK”.
![Push repo to GitHub][image-13]
- Finally, hit the “Push” button from the top bar.
- Select the “master” checkbox. Then hit “OK”.
- You will be asked to enter your GitHub.com credentials. If you are on a Mac, I would save these in your keychain. 


#### Success Pushing
To verify success in pushing the repo, go to GitHub.com. You should see “341-work” under “Your repositories”.

Select your 341-work repository. You should see the files you added to your repo on the GitHub.com site. 
![The 341 repo on GitHub][image-14]

You can now select any of these files to view their contents. 

Likewise, you can select the “commits” tab to see all of the commits you have made in your repo so far. 
 

[1]:	https://github.com
[2]:	https://opensource.org/osd
[3]:	https://github.com/

[image-1]:	imgs/gh_signup.jpg
[image-2]:	imgs/gh_setup1.jpg
[image-3]:	imgs/gh_setup2.jpg
[image-4]:	imgs/gh_setup3.jpg
[image-5]:	imgs/gh_setup4.jpg
[image-6]:	imgs/st_setup4.jpg
[image-7]:	imgs/repo_setup2.jpg
[image-8]:	imgs/repo_setup3.jpg
[image-9]:	imgs/repo_setup4.jpg
[image-10]:	imgs/repo_setup5.jpg
[image-11]:	imgs/repo_setup6.jpg
[image-12]:	imgs/repo_setup7.jpg
[image-13]:	imgs/repo_setup8.jpg
[image-14]:	imgs/gh_341_repo.jpg
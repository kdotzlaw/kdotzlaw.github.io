# **How to Host a Resume Using Jekyll**
## Purpose: 
* Provide a step-by-step guide on how to host and format a resume written in Markdown (edited in Notepad++), hosted by Jekyll and GitHub Pages.
* Relate the general principles of technical writing to each step in the guide given. The general principles are described in Andrew Etter's book, [_Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=36CB5TXK2RFM8&keywords=modern+technical+writing+by+andrew+etter&qid=1667241539&qu=eyJxc2MiOiIwLjAwIiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=%2Caps%2C121&sr=8-1).
## Prerequisites:
* You will need a resume written in Markdown. For a Markdown tutorial, go [here](https://www.markdowntutorial.com/).
* You will need a GitHub account. For information on creating an account, go [here](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account). 
## How to Host and Format a Resume Using Markdown, Jekyll and GitHubPages
### Create a Site
This section will demonstrate how to create a new site using Jekyll. Jekyll converts Markdown files to HTML files. One of Andrew Etter's key principles is to use a lightweight markup language. By using Jekyll and Markdown, we are following Etter's tenet that everyone could be a contributer, since Markdown is easy to learn and use.
1. Install Jekyll prerequisites, found [here](https://jekyllrb.com/docs/installation/).
2. Open your command prompt. 
* For Windows, search 'cmd' in the Start menu. Information for other systems can be found by searching 'command prompt <operating system>'.
3. Install Jekyll, following the steps for your operating system found [here](https://jekyllrb.com/docs/installation/).
4. Go to the directory you want to store your site in using the command prompt. 
* Go [here](https://www.wikihow.com/Find-All-Commands-of-CMD-in-Your-Computer) for information on how to find command prompt commands on your computer.
5. Create a new Jekyll site using **jekyll new <site_name>**
6. Go into the directory **<site_name>.
7. Build your site using **bundle exec jekyll serve**
Congratulations! You have created your first Jekyll site! You can search **localhost:4000** in your web browser to view your new site.
### Creating Your Website's Repository
This section demonstrates one of Andrew Etter's key principles: version control. It is good practice to store code and documentation together. As Etter explains in _Modern Technical Writing_ , storing code and documentation together allows them to stay in sync.
1. Create a new repository by clicking the **+** button.
2. Name your repository **<GitHub_Username>.github.io**.
3. Publish your repository.
You have now created a repository for your website.
### Adding GitHub Pages
This section will demonstrate how to add GitHub Pages to your repository.
1. Go to **settings**.
2. Click **Pages** in the **Code and Automation** section.
3. Select the branch to add GitHub Pages to.
* For our purposes, the main branch is fine.
4. Wait for GitHub Pages to finish building.
You have now added GitHub Pages to your repository.
### Host Your Resume
This section includes information on uploading your resume and hosting it using GitHub Pages. As explained in _Modern Technical Writing_, hosting content on a website allows content to be easily updated and keep information current.
1. Click **upload file** under the **add file** section.
2. Open your **<site_name>** folder in your documents.
3. Open the **_site** folder.
4. Drag all the files in the **_site** into the **upload file** section.
5. Commit your changes.
6. Return to your **<site_name>** folder.
7. Copy the contents of your resume.
8. Paste the contents into the **index.markdown** file.
9. Go into the **_posts** folder 
10. Delete the default post.
11. Search **<gihub_username>.github.io** in your internet browser.   
![Alt Text](kdotzlaw.github.io/for_readme_a2.gif)   
Congratulations! You have hosted your resume using Markdown, Jekyll and GitHub Pages!
## Authors and Acknowledgements
I would like to acknowledge Tristan Dyck, Asifur Rahman and Aneesh Makkar for their help editing this guide.
## FAQs
**Why is Markdown better than a word processor?**   
Markdown is better than a word processor because formatting is fast and easy. Markdown's syntax allows formatting to be done without clicking different buttons.
**Why can't I run Jekyll?**   
Jekyll requires Ruby so make sure you have at least Ruby 2.50 installed. You can check your version of Ruby by opening the command prompt 
(for Windows, search 'cmd' in the Start menu) and typing **ruby -v**). If your version of Ruby is too low, uninstall 
it using the **Add or Remove Programs** functionality on your computer. Now you can install the newest version of 
Ruby found [**here**](https://rubyinstaller.org/downloads/). 




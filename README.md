# **How to Host a Resume Using Markdown, Jekyll and GitHub Pages**
## Purpose: 
* Provide a step-by-step guide on how to host and format a resume written in Markdown (edited in Notepad++), hosted by Jekyll and GitHub Pages.
* Relate the general principles of technical writing to each step in the guide given. The general principles are described in Andrew Etter's book, [_Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=36CB5TXK2RFM8&keywords=modern+technical+writing+by+andrew+etter&qid=1667241539&qu=eyJxc2MiOiIwLjAwIiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=%2Caps%2C121&sr=8-1).
## Prerequisites:
* You will need a resume written in Markdown. Refer to the **More Resources** section for a Markdown tutorial.
* You will need a GitHub account. Refer to the **More Resources**  section for information on creating an account.
## How to Host and Format a Resume Using Markdown, Jekyll and GitHubPages
### Create a Site Using Jekyll
This section will demonstrate how to create a new site using Jekyll and two of Andrew Etter's principles of good technical writing.  

In his book _Modern Technical Writing_, Etter describes the importance of writing technical documents using a lightweight markup language. 
Lightweight markup languages are both free and easy to use. As stated by Etter, lots of companies do not have a technical writing team 
and the ease of using a lightweight markup language allows anyone to be contributers.  

The second principle demonstrated is using a static site generator. Static site generators (like Jekyll) allow any files written in a lightweight 
markup language to be converted into HTML automatically. These sites are generated without databases or dependencies, allowing them to be relocated and changed easily. 
This emphasizes Etter's point about anyone being able to contribute. 
#### Instructions
1. Install Jekyll prerequisites, found [here](https://jekyllrb.com/docs/installation/).
2. Open your command prompt. 
	* For Windows, search 'cmd' in the Start menu. 
	* Information for other systems can be found by searching 'command prompt <operating system>' in your web browser.
3. Install Jekyll, following the steps for your operating system found [here](https://jekyllrb.com/docs/installation/).
4. Go to the directory you want to store your site in using the command prompt. 
	* Go [here](https://www.wikihow.com/Find-All-Commands-of-CMD-in-Your-Computer) for information on how to find command prompt commands on your computer.
5. Create a new Jekyll site using `jekyll new <site_name>`
6. Go into the directory **<site_name>**( `cd <site_name>` for Windows) .
7. Build your site by typing `bundle exec jekyll serve` into the command prompt.   
Congratulations! You have created your first Jekyll site! You can search **localhost:4000** in your web browser to view your new site. You have also learned 
how the instructions for creating a static site relate to Andrew Etter's key principles.

### Setting Up GitHub Pages
This section demonstrates one of Andrew Etter's key principles: version control. Additionally, it will provide instruction on how to 
create a repository for your website.
It is good practice to store code and documentation in the same repository. In addition to being good practice, it encourages contribution. Andrew Etter states that developers who have to 
clone a seperate repository are less likely to contribute to the project.
Etter also explains in _Modern Technical Writing_ that storing code and documentation together allows them to stay in sync. 
#### Instructions
1. Create a new repository    
 a. Create the repository by clicking the **+** button.   
 b. Name your repository **<GitHub_Username>.github.io**.   
 c. Publish your repository.   
You have now created a repository for your website. You have also learned about the importance of version control, another of Andrew Etter's key principles.      
2. Add GitHub Pages   
 a. Go to **settings**.   
 b.  Click **Pages** in the **Code and Automation** section.   
 c.  Select the branch to add GitHub Pages to. For our purposes, the main branch is fine.   
 d. Save your changes.  
3. Wait for GitHub Pages to finish building.
You have now added GitHub Pages to your repository. You have also learned about Etter's principle of version control. 
### Host Your Resume
This section includes information on uploading your resume and hosting it using GitHub Pages. Additionally, it demonstrates Andrew Etter's principle of using a static site generator.
As explained in _Modern Technical Writing_, hosting content on a website allows content to be easily updated and keep information current. 
He emphasizes the convenience of immediately fixing errors when hosting files online. 
#### Instructions
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
![Alt Text](for_readme_a2.gif)   
Congratulations! You have hosted your resume using Markdown, Jekyll and GitHub Pages!
## Authors and Acknowledgements
I would like to acknowledge Tristan Dyck, Asifur Rahman and Aneesh Makkar for their help editing this guide.
## More Resources
* For a Markdown tutorial, go [here](https://www.markdowntutorial.com/).
* For information on creating a GitHub account, go [here](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account). 
* [Here](https://idratherbewriting.com/2016/07/26/modern-technical-writing-review/) is a really good review of _Modern Techical Writing_ that ephasizes Etter's key principles.
## FAQs
**Why is Markdown better than a word processor?**   
Markdown is better than a word processor because formatting is fast and easy. Markdown's syntax allows formatting to be done without clicking different buttons.  

**Why can't I run Jekyll?**   
Jekyll requires Ruby so make sure you have at least Ruby 2.50 installed. You can check your version of Ruby by opening the command prompt 
(for Windows, search 'cmd' in the Start menu) and typing **ruby -v**). If your version of Ruby is too low, uninstall 
it using the **Add or Remove Programs** functionality on your computer. Now you can install the newest version of 
Ruby found [**here**](https://rubyinstaller.org/downloads/). 




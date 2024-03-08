# Creating a static Website for Resume

### Purpose:
1. Describe how to create a static website using Markdown and GitHub.
2. Refer to Etter's book to explain why the step is important.

### Prerequisites:
You must be able to create a text file using Markdown. If you do not know how to create a markdown file, then go to [more resources](#More-resources) section. A link is provided to learn how to create a Markdown file.

### Instuctions:

#### 1. Use Lightweight Markup language to create your resume
Create a resume that you want to show on the website. Use Markdown to create this file.

*Lightweight Markup is important as it is the key to creating a static website. The reason being static website generator will create a website for you, but it does not know what to show on there. Website generators will create the website and show what you write on your text file that you supplied it with.*

*Etter talks in his book about the importance of using lightweight markup. He shows how complex it can be to write a sentence with code that can be easily written using a lightweight markup language.*

*What makes it great is that it is:* 

* *Easy to learn*
* *Human readable*
* *Requires no coding*

*Markdown is a lightweight markup language. Markdown is extremely popular and widely used by static website generators. It is also quite easy to use as well. Since it is a lightweight markup language, creating a resume will be easy and fast.*

#### 2. Use GitHub as your version control system

 1. Create an account on GitHub.
 2. Create a repository.
    
    If you do not know how to create a repository then go to [more resources](#More-resources) section. There is a link to help you create a repository. Once that is done, upload the resume you created on this repository.

      > Note: When creating the repository, you must name it ```username.github.io```. Replace ```username``` with your account username. This is important because with this, GitHub recognizes  that you want to create a static website.

      *Etter talks about version control systems and how important it is. A version control software is important to a programmer since it helps them keep track of their projects and files. Although he talks about how it is useful for programmers, it is also useful to us as well.*

      *Once the file is uploaded and committed, we can make as many changes as we want to the resume. There is a possibility that you might want to change the content after some time. Even after these changes, if something goes wrong, we will not lose our data. We can recover it. This way you will not have to create the website from the beginning.*

 3. Create your static website

      1. Once the file is uploaded, go to settings and then to pages as shown in this image.
    
    ![](files_for_README/Twelth.png)

      2. Navigate to Branch after that.
    
    ![](files_for_README/TwelthBox.png)

      3. Click on the box that says none, and from the options given, click on main. Then click on the save button to finish.
    
    ![](files_for_README/gif_me.gif)

      Now GitHub will start creating your website. It may take few minutes to several minutes. Once it is done, you can visit your website by searching ```username.github.io```.

      > Note: Make sure to change the ```username```.

      *Etter explains what makes a static site generator so great. The site generator does everything for you. You only have to create a text file that the site generator can go through.*

      *It is great because:*
      * *There is nothing to install*
      * *You do not have to worry about application dependencies*
      * *Working with the website is easy*
      * *The site creates the website for you*
      
      *This makes sites like GitHub and many others a great tool.*

#### 3. Format your resume by giving it a style
1. Create a file named ```_config.yml```. Make sure to have the underscore in front of the name as shown here.
2. Add ```theme: jekyll-theme-modernist``` in it
3. Commit the file to confirm the changes

Now your file has theme to it like my website below.

![](files_for_README/GIFMaker_me.gif)

*Adding a theme is important. Imagine having a website with just text on it. Without themes, it looks plain and boring. Etter describes the importance of style. Having lists, pictures, and other style makes your writing more approachable. It becomes simpler to go through unlike having to go through just plain text file.*


### More resources:
[Markdown](https://commonmark.org/help/tutorial/): For understanding more about markdown.

[Repositories](https://docs.GitHub.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories): To learn and create repositories on GitHub.

[GitHub Pages](https://docs.GitHub.com/en/pages/getting-started-with-GitHub-pages/creating-a-GitHub-pages-site): For more information on creating a website on GitHub.

[GitHub Pages themes](https://docs.GitHub.com/en/pages/setting-up-a-GitHub-pages-site-with-jekyll/adding-a-theme-to-your-GitHub-pages-site-using-jekyll): These are the supported themes of GitHub Pages that you can use for your website.


### Authors and Acknowledgements:
This project is made possible by GitHub and Etter's book "Modern Technical writing: An Introduction to Software Documentation". Thanks to GitHub for providing the tools necessary to create this project. My understanding of static websites comes from Etter's book so, thanks to Etter's book that helped me understand the importance of each of the steps shown above.

### FAQs:
#### Why should I use GitHub in creating the website when there are other means?

There are many other ways to create a static website but not all of them are as easy as GitHub. Also, unlike the others, GitHub is a version control system which allows you to keep track of the files. So, if there is a mistake in your file that GitHub uses to create the website, you can go back to the old version easily.

#### Why is my website not showing up?

There are many reasons as to why this is happening. Some of them are:
    
1. Your repository name is not username.GitHub.io. The website can be created with different names like resume.GitHub.io as long as GitHub.io is in your repository name. If so, then only the website link changes. Which would now be username/repository_name.GitHub.io.
2. You have not told GitHub that you want a website. To solve this problem follow the instuction step number 3 above which is ["Use GitHub to create a static website"](#3-use-GitHub-to-create-a-static-website).

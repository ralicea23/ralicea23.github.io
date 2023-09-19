# My First Hugo Static Website

Welcome to my first Hugo static website! I'll provide you with a brief guide on how to create a Hugo website and how to add it to GitHub.
Prerequisites

Before you begin, make sure you have the following prerequisites installed on your computer:

    Hugo: Hugo is a fast and flexible static site generator. You can download it from Hugo's official website.

    Git: You'll need Git for version control and to push your website to GitHub. You can download Git from here.

## Getting Started

### Follow these steps to create your first Hugo static website and add it to GitHub:
1. Create a New Hugo Site

Open your terminal and run the following commands to create a new Hugo site:

bash
```
# Create a new Hugo site (replace "my-hugo-website" with your desired project name)
hugo new site my-hugo-website

# Change directory to your new Hugo site
cd my-hugo-website
```
2. Choose a Theme

Hugo supports various themes. You can find a theme you like on the Hugo Themes website. After selecting a theme, follow the theme's documentation to add it to your site.
3. Create Content

You can create new content (e.g., blog posts) using Hugo's built-in command:
```
bash

hugo new posts/my-first-post.md
```
Edit the markdown file to add your content.
4. Customize Your Site

Hugo allows you to customize your site's configuration and layout. Edit the config.toml file to configure your site settings and customize the theme to your liking.
5. Preview Your Site

To preview your site locally, run the following command:
```
bash

hugo server -D
```
Your site will be available at http://localhost:1313/.
6. Build Your Site

Once you're satisfied with your site, build it using the following command:
```
bash

hugo
```
This will generate the static files in the public directory.
7. Create a GitHub Repository

Go to GitHub (https://github.com) and create a new repository to host your website.
8. Initialize Git and Push to GitHub

Back in your terminal, initialize a Git repository in your Hugo project folder:
```
bash

git init
```
Add your files, commit them, and set the remote repository URL:
```
bash

git add .
git commit -m "Initial commit"
git remote add origin <your-github-repo-url>
```
### Finally, push your Hugo website to GitHub:
```
bash

git push -u origin master
```

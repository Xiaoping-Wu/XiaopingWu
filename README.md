# Make my own website with R Markdown and git

## Procedure 1: prepare your info by Rmarkdown

- create a project folder in R

- create Modify _site.yml, index.Rmd, about.Rmd with your own content

- Build the website by running rmarkdown::render_site(encoding = "UTF-8")

## Procedure 2: Using git to connect to github

### step 1: Git configuration

- install git

- Open "Command Prompt", and go to your R project directory.

- Run "git status", get message: fatal: not a git repository (or any of the parent directories): .git

- Run "git init" to connect your R project folder as a local github repository

- Run "git config --global user.name myname"

- Run "git config --global user.email  my email"

- Run "git status" to check your status

### step 2: create a new repository in github, copy url

### step 3: Connect local and github repository

- back to "command prompt" in local computer

- Run "git remote add origin $url"

- Run "git remote –v" to check if remote succeed 

- Run "git branch" to check branch

### step4: create a README.md file in current folder and track it

- Run "git add README"

- Run "git status" check statuus changed

- Run "git commit README" to update README file and describe changes

- Run "git push origin master" to push to remote server


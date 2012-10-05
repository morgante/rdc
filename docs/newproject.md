New Project Guide
===

This guide describes how to set up a new student government project.

### Create GitHub Project
Create a new project on [GitHub](https://github.com/new) owned by ```nyuadsg```.

### Set up the project architecture
First, clone the ***nyuadsg/template*** repository locally, and enter it.

    git clone https://github.com/nyuadsg/template.git OurProject
    cd OurProject

Then, set up all our branches properly:

    git fetch --all
    git checkout admin
    git checkout beta
    git checkout production
    
### Point your local copy to the GitHub copy
We now need to change your local repository so it points to the new GitHub one for our project, instead of template.
    
    git remote set-url origin https://github.com/nyuadsg/checkout.git
    
### Push the architecture to GitHub
Finally, we just need to push the architecture you just created to GitHub.

    git push --all
# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

- Assuming we're starting from scratch one would first create a local directory using `mkdir <directory_name>`.
- One would navigate into the directory using `cd <directory_name>` 
- One would then initialize git using `git init`
- One would next make a file using `touch <filename.extension>`
- Next one would add their current file to the local git repository with `git add <filename.extension>` 
- One woudl make the initial commit using `git commit -m "Initial commit"`
- And finally one would open in vs code using `code .`
---
- Next we must create a remote repository on GitHub on our web-browser and give it the same name (or something similiar) as the directory we just established earlier. You can do this from your profile on GitHub using the "+" in the top right of the page on your profile. Select "New Repository". Give your repository a name and hit the green "Create Repository" button on the bottom. 
- Once this remote repositroy is established it will create a unique origin key that we can copy. Make sure the "SSH" button is selected and not the "HTTPS". 
---
- Back in the terminal enter `git branch -M main` to establish the main branch of the git workflow tree (Is this step optional?)
- Enter `git remote add origin <SSH key from GitHub remote repository>`
- Enter `git push -u origin main`
- The two repositories should now be connected and one can just enter `git push` to get new entries to the remote repository because we've established the remote repository as the main origin. 


## Things to be aware of

1. Don't make a directory for something you're going to `git clone`, it will happen when you clone the repository.
2. Make sure you are `git add`ing and `git commit`ing the FILE not the directory, ya donkey. 
3. You can just `git push` the file once you've cloned it. You don't need to establish the branch origin or any of that fancy ssh stuff (Because you already added it when you cloned the repository)
---


- Try going back and re-doing the two exercises

## NEW HEADER

- I think I got it? 
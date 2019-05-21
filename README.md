# 💪 Welcome to Git 101 Workshop Challenges! 💪

If you haven't installed git, please see instructions below.

Solve the following challenges with your workshop buddy (pair programming).

**Cheatsheet** for [Mac & Linux Users](https://www.slideshare.net/secret/Ba69kgSROEBNNL)<br/> **Cheatsheet** for [Windows Users](https://www.slideshare.net/secret/BjwZiFSFdAhMVP)

### Challenge 1
1. Using the terminal make sure your working directory is set to desktop.
2. On GitHub **Fork** the repositiory (so that you are the Master of that repository) >> <img width="115" alt="Screen Shot 2019-03-27 at 11 08 03 am" src="https://user-images.githubusercontent.com/21133601/55041327-acffec00-5080-11e9-8850-1def8d348331.png">
3. `git clone` your new repository onto your Desktop 
4. `cd` into that repository.

### Challenge 2
1. Create a new branch and `git checkout` into it.
2. Update the HTML file with your name and a star beside it then save your file.
3. To save your new version, first `git add` the updated HTML file. 
4. Then commit the changes on that branch with a message: `git commit -m "write a unique message"` 
5. Run `git remote -v` to see what remote repository is linked to your project.
6. Finally, git push your branch to GitHub. (Make sure to push the branch using `git push origin branch-name`) 

### Challenge 3
1. On GitHub, open a Pull Request on GitHub for me to review.
2. If your Pull Request got accepted, your changes are added to the [Hall of Fame](https://allthatjoy.github.io/git-101-women-who-code/)<br>



### Bonus Challenge - Get familiar with the terminal and Git (Use your Cheatsheet)
1. Open your terminal .
2. Create a new folder on your Desktop using your command line.
3. Find the command to change to that folder (directory).
4. Inside your new directory, create a new file called text.txt
5. Initialize git for that directory.
6. On your Desktop, open that file with a text editor. 
7. Write "Github 101" in that file, close it and save the file.
8. Which Git command do you use to review what changed in the HTML? 
9. Make a new commit with a message to describe the changes you made. 
10. Create a new branch and jump onto that branch. How do you know how many branches there are in the project? How do you know which branch you are on?
11. Now, `git checkout` to your master branch and then merge your branch to the master branch.
<br>
<br>

|  | Git Installation |
| ------ | ------ |
| 1 | In your terminal, run the command: `git version`. If Git is not installed, you can find the install file [here](https://git-scm.com/downloads)
| 2 | Set your username and email on git. To set username, run `git config --global user.name “your name”`. To run your email : `git config --global user.email “your email”`

|  | Optional: To make your terminal more user-friendly, **install oh-my-zsh** |
| ------ | ------ |
|   | **For Mac & Linux Users**: The installations instructions are [here](https://github.com/robbyrussell/oh-my-zsh). You can also just run this command in your terminal: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
|   |**b) For Windows 10 Users**: You can find installations instructions [here](https://www.maketecheasier.com/install-zsh-and-oh-my-zsh-windows10/), but the process is much much longer, so it is recommended that you do this at home. 

Hello World! I'm doing the Git Challenge!

I'm practicing adding changes to my file and commiting the new changes.
So far I know about git init, git status, git add, git commit and now I wanna learn about git diff.

Still trying to figure git diff out...

OK! That's done. So to use git diff, I need to remember that in order to see the changes or the differences between file 
I must diff before commiting. The comand is git diff <filename>

Now I'm experimenting with the remote. IMPORTANT to git remote add origin <urlfromgithub>
And after putting username and password you can push yoour local into the remote.
For that I use git push origin master. So in this case we'll send our branch named 'master' to our 
remote on GitHub named 'origin'. 

Now I learned about forking. When you forked a repo you are creating a copy of it on your GitHub account.
This fork begins his life as a remote repo. Forks are used for creating your own version of a project or
contributing back with fixes or features to the original project. 

Once the project is forked in your GitHub account the you can clone it to your computer and work locally.

So for adding remote connections we use git remote add <REMOTENAME> <URL>  and for viewing then we use 
git remote -v 

Let's talk about branches...

Git repositories use branches to isolate work when needed. It's common practice when working on a project or 
with others on a project to create a branch to keep your changes in until they are ready. 
This way you can do your work while the main, commonly named 'master', branch stays stable. 
When your branch is ready, you merge it back into 'master'.

When you create a branch in your project, you're creating an environment where you can try out new ideas. 
Changes you make on a branch don't affect the master branch, so you're free to experiment and commit changes, 
safe in the knowledge that your branch won't be merged until it's ready to be reviewed by 
someone you're collaborating with.

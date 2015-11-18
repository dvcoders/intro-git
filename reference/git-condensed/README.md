# Git Condensed

1. Clone a repository from Github
	
	`$ git clone url`
	
2. Create a branch for your additions

	`$ git checkout -b "new-feature"`
	
3. Make changes
4. "Stage" your changes so git tracks them

	`$ git add file1 file2` OR `$ git add -A`
	
5. Commit your changes (locally, just on your computer)
	
	`$ git commit -m "description of changes"`
	
6. Push those changes to the Github repository
	
	`$ git push origin branch-name`
	
	- "origin" refers to the url of the repository, which is the same as the url you cloned from
	
7. Repeat steps 3 to 6 until finished with your additions

	- `$ git status` often, maybe after every command when you first start

## If you're working with other people:

1. After finalizing your additions, make a "pull request" from branch-name to base: master
	
	![](http://i.imgur.com/h4gqAss.png)
	
2. Assign someone to review your code
3. Go back to the steps above if changes need to be made
4. Merge

	![](https://raw.githubusercontent.com/dvcoders/intro-git/master/workshop/screenshots/merge-pull-request.png)

5. Hope there are no merge conflicts
6. Done!

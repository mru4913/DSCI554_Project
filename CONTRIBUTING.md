# Contributing

In this project, we will be using git as the version control system for our work. By participating in this project, each group member should agree to abide by the [code of conduct](https://github.com/UBC-MDS/DSCI554_Project/blob/master/CODE_OF_CONDUCT.md). Each group member will fork the main repository into their personal repository. They will work locally, and send pull-requests of their update to the main repository. At least one other team mate will review,  critique (if necessary), and finally accept their team mate's pull request. Each contributor will also use GitHub issue to communicate to their team mates regarding any problems, ideas and concerns.

The full instructions can be found from the [Github guides to Forking](https://guides.github.com/activities/forking/).

### Example of a contributing workflow:

Fork, then clone the repo:
```
git clone https://github.com/UBC-MDS/DSCI554_Project.git
```

Make changes, then push the repo:
```
git add .
git commit -m "<meaningful_message>"
git push
```

Check if the main repo is added as a remote repo:
```
git remote -v
```

If the main repo is not added:
```
git remote add upstream <original_repo_URL>
```

If the current `master` branch falls behind the forked branch:
```
git fetch upstream
git merge upstream/master
git push
```
Push to your fork and submit a pull request for other team mates to review.

Contributing document derived from [Thoughtbot](https://github.com/thoughtbot/factory_bot_rails/blob/master/CONTRIBUTING.md).

A properly formed git commit subject line should always be able to complete the following sentence

If applied, this commit will <your subject line here>

# Commit Guideline

### Rules for a great git commit message style
* Separate subject from body with a blank line
* Do not end the subject line with a period
* Capitalize the subject line and each paragraph
* Use the imperative mood in the subject line
* Wrap lines at 72 characters
* Use the body to explain what and why you have done something. In most cases, you can leave out details about how a change has been made.

### Information in commit messages
* Describe why a change is being made.
* How does it address the issue?
* What effects does the patch have?
* Do not assume the reviewer understands what the original problem was.
* Do not assume the code is self-evident/self-documenting.
* Read the commit message to see if it hints at improved code structure.
* The first commit line is the most important.
* Describe any limitations of the current code.
* Do not include patch set-specific comments.

### Example of a commit for update

```
git commit -m "Update <file> with <action>"
git commit -m "Create <file>"
git commit -m "Delete <file>"
git commit -m "Add <file> for <purpose>"
```

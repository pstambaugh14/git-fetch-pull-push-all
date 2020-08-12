# pstambaugh14/git-fetch-pull-push-all

## QUICK INTRO

Git Linux BASH Script to Update ALL Projects Under Parent Directory for any Git Project using Branch/Tag Origin 'Master'.

## From Remote to Local:
- Fetch
- Pull

## From Local to Remote:
- Add
- Commit
- Push

## Credits

- Please check: https://github.com/pstambaugh14/git-fetch-pull-push-all

# Overview
- Simple script to help keep all Git projects up-to-date if using 'master' branch/tag.   
## WARNING!~
- If anyone else uses this script, just please be aware that this is strictly for my personal use at the moment and I am not being held responsible if anything happens to your system by using this script.  

# Completed Goals!:
- Skip completely (not execute anyway) git-based commands while running the script in non-git directories. ( idea: [if exists directory/file...? = git-based]. - Check!
- Possibly have the script search the entire filesystem for any .git folders to automate process (rather than just function under one parent directory). - Check!

# New Goals:
- Enable Configurations for different tags/branches other than just 'master'.
- Create securely-stored credentials to pass from a file and source into script rather than have prompts.
- Also remove prompts for commit changes and create one default and/or have it configurable via config file sourced into script?
- Add Git Permissions Fix Script Also!

-----------------------------------------------------------------------------------------------------------------------------

# Overall Goal of This Project
Depending on the parent directory specified by the user during runtime prompts, this script will find all Git projects under that parent directory by finding .git folders in each repository.  From there, the script will attempt to automatically git: fetch, pull, add, commit and push to update both the local repositories as well as the remote GitHub repos - in order to keep everything in sync as best as possible!

The only thing that I'd really need to iterate is the fact that upon running this script, the user should be absolutely sure that's what he/she wants to do! ie - know that you'll be getting the latest SCM upon either the remote or local repository depending upon the order of changes in git between the two nodes.

So, this could be really cool but USE IT WITH CAUTION! =D

# Credits:
Git, Linus Torvolds, Linux / GNU, GitHub.

## License
Created by Patrick Stambaugh.
https://github.com/pstambaugh14/git-fetch-pull-push-all

## USAGE INSTRUCTIONS
Installation:

To Download:
```sh
git clone https://github.com/pstambaugh14/git-fetch-pull-push-all.git
```
To Install:
```sh
cp git_fetch-pull-push_all.sh <your_parent_git_directory>
```

To Run:
```sh
./git_fetch-pull-push_all.sh
```

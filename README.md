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

# New Goals:
- Enable Configurations for different tags/branches other than just 'master'.
- Skip completely (not execute anyway) git-based commands while running the script in non-git directories. ( idea: [if exists directory/file...? = git-based].
- Create securely-stored credentials to pass from a file and source into script rather than have prompts.
- Also remove prompts for commit changes and create one default and/or have it configurable via config file sourced into script?
- Possibly have the script search the entire filesystem for any .git folders to automate process (rather than just function under one parent directory).

-----------------------------------------------------------------------------------------------------------------------------

# Overall Goal of This Project
If you have a lot of Git projects under one directory, then this script can help keep all of your projects up-to-date locally and remotely just by running this script.  This is very basic at the moment and WILL overwrite every (local + remote) Git project under the parent directory to whatever is the latest SCM.

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

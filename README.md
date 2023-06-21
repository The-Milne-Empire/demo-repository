# Project Roadmap

Version 1.0.0 - Due 6/22/2023

- Change h1 text to say "Hello, World!"
- Add a button that counts how many times it's been pressed



## Prereqs:
[Install GitHub CLI](https://cli.github.com/)

# Forking the repo
I prefer to do this on gh website

Go to hatchery/repo-name
Create a new fork

# Contributing
1. Create a branch with the name being the issue you are resolving
2. Checkout branch
3. Once resolved the webpage for the Hatchery repo would ask for a pull request
4. Fill out necessary description and title
5. Force merge for simple things or code review and get checked off for major changes
6. Sync fork (see below)
7. Checkout main branch
8. Delete branch (make sure done on remote and local repo)
9. Close relevant issue

# Syncing up with main branch of org repo

1. git remote add upstream [gh repo url] (Only need to do first time)
2. gh repo sync The-Milne-Empire/demo-repository -b main
3. git pull
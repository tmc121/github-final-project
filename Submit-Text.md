# Submission URLS

readMe.md
https://github.com/tmc121/github-final-project/blob/36ebed1511bdb0a4f724a0fd53d43afdbb741915/README.md

license
https://github.com/tmc121/github-final-project/blob/36ebed1511bdb0a4f724a0fd53d43afdbb741915/LICENSE

contributions.md
https://github.com/tmc121/github-final-project/blob/36ebed1511bdb0a4f724a0fd53d43afdbb741915/CONTRIBUTING.md

code-of-conduct.md
https://github.com/tmc121/github-final-project/blob/36ebed1511bdb0a4f724a0fd53d43afdbb741915/CODE_OF_CONDUCT.md

simple-interest.sh
https://github.com/tmc121/github-final-project/blob/c9eda4fdf82c264ebe99ddbf51b1af356ce7ae23/simple-interest.sh

# FORK-REPO
theia@theia-terellmcross:/home/project/mcino-Introduction-to-Git-and-name>/mcino-Introduction-to-Git
GitHub$ curl curl -s https://api.git
hub.com/repos/tmc121/mcino-Introduction-to-Git-and-GitHub | jq -r '.parent.clone_url'
https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub.git
theia@theia-terellmcross:/home/project/mcino-Intro
duction-to-Git-and-GitHub$ 

#



//
theia@theia-terellmcross:/home/project$ cd mcino-Introduction-to-Git-and-GitHub
theia@theia-terellmcross:/home/project/mcino-Introduction-to-Git-and-
GitHub$ git push origin bug-fix-revert
Username for 'https://github.com': tmc121
Password for 'https://tmc121@github.com': 
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'bug-fix-revert' on GitHub by visiting:
remote:      https://github.com/tmc121/mcino-Introduction-to-Git-and-GitHub/pull/new/bug-fix-revert
remote: 
To https://github.com/tmc121/mcino-Introduction-to-Git-and-GitHub.git
 * [new branch]      bug-fix-revert -> bug-fix-revert
theia@theia-terellmcross:/home/project/mcino-Introduction-to-Git-and-
GitHub$ curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/<Pull-Request-ID> | jq -r '.head.repo.clone_url'
bash: syntax error near unexpected token `|'
theia@theia-terellmcross:/home/project/mcino-Introduction-to-Git-and-
GitHub$ curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/bug-fix-revert | jq -r '.head.repo.clone_url'
null
theia@theia-terellmcross:/home/project/mcino-Introduction-to-Git-and-
GitHub$ git branch -vv
  bug-fix-repo   ad95b0a Create close_pr.yml
* bug-fix-revert 04f0cd2 Fix typo in README footer
  bug-fix-typo   04f0cd2 [origin/bug-fix-typo] Fix typo in README footer
  main           04f0cd2 [origin/main: ahead 1] Fix typo in README footer

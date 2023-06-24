# Boilerplate creation algorithm:


1. Create npm project by 'npm init'
2. Add ESLint linter support by 'npm init @eslint/config'. Crediting Timur Shemsedinov for [ESLint config example](https://github.com/HowProgrammingWorks/Tools/blob/master/JavaScript/examples/.eslintrc.json)
3. Add Git by 'sudo apt-get install git'. Then create remote repo in GitHub. Then use this [GitHub guide](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-using-git)
4. Add .gitignore file to ignore all unnecessary files/folders which need not to be in the version control. Crediting Timur Shemsedinov for [.gitignore config example](https://github.com/HowProgrammingWorks/Tools/blob/master/JavaScript/examples/.gitignore) 
5. Add .travis.yml Travis CI file to let it know what to do in repository. Configure it as you wish or take my [example]
6. After successfull build you can add the Travis build resulsts icon from https://travis-ci.org/{username or org}/{repository} like this:
[![Build Status](https://app.travis-ci.com/ddziuman/environment-setup.svg?branch=master)](https://app.travis-ci.com/ddziuman/environment-setup)
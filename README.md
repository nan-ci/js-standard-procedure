## Standard Procedure

You first need to *fork* the exercise git repository.

![forking](https://raw.githubusercontent.com/nan-ci/js-standard-procedure/master/fork.png?sdsd)

> :warning: Ensure you are on the root directory (path should start with: **nan-ci/**)

Once that's done, you can clone your repository like so:

    # repo-url can start by ssh or https
    # your login must appear somewere in the url
    git clone repo-url

    # then you can cd in your repository
    cd repo-name

then create a JavaScript file named `index.js` in which you will write your code.

    # To test your current solution you need to install the dependencies :
    npm install

    # Then you can run the tests
    npm test

    # The old wisdom says: Test often, Test early

    # To submit your progress
    git add index.js # add the file
    git commit -m "commit message" # name your changes
    git push -u origin master# save them on the server
    # You only need -u origin master the first time just `git push` after that

But if you are stuck pause and think about your problem.
Don't try to find the solution *by chance* that always end up taking more time.

Don't forget to commit your changes and push them to server often and not do it
all at the last minute.

You write code for humans, not machines, write meaningfull variables,
functions, commits, help others understand your code.

You will always be able to come back and update your solution but your
last commit of the day is the one that will used as your submited answer.

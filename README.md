# flicklist

FlickList 0

This is a series of studios building on the Flicklist project.  This commit is about getting set up.

(Original instructions below.)

The starter code for the project is obtained, as follows:  
 1.  sign into github.com
 2.  go to https://github.com/LaunchCodeEducation/flicklist
 3.  fork the project (click on the "Fork" button)
 4.  this takes you to a new page:  yourusername/flicklist
 5.  clone your fork onto your own machine:
     from the terminal ("Git Bash"), cd into the parent folder where you want to save the project
     $ git clone https://github.com/YOURUSERNAME/flicklist.git
     (there should now be a new folder called flicklist, us ls to see it)
     $ ls
     $ cd flicklist/
     $ ls
     (you have cloned the entire finished project, there will be 6 branches - one for the next 6 studios)
 6.  check out the new branch:
     $ git checkout studio0
     (you have now switched to a new branch called 'studio0')
 7.  Review Starter Code:
     In index.html, there is hardcoded text which will appear on the browser screen.
        Complete the TODO:  finish the <script> tag so that it loads up the local flicklist.js file
     In flicklist.js, a javascript object is stored in a local variable called api
        There is also a function called testTheAPI(), that tests the ability to connect to themoviedb's API. 
           It does so by making making an AJAX request (using jQuery's .ajax function) to this url:
           "https://api.themoviedb.org/3/discover/movie", passing along your API key as a parameter.
           A success "callback" function is provided to the request, which will be invoked if a response comes back successfully.
           This callback function will log the response to the console.
        After defining the function, we have a simple console.log statement, and then we invoke the function.
  8.  Register for an API key with themoviedb.org
      (themoviedb.org is an open source database of movies and TV shows.  The code uses its API as the source of the project's data.
      This API requires that you register and obtain a key in order to use it.)
      To register for a key:
      Sign up for an Account by clicking 'Register here' and completing the information requested.
      Check your email and click the confirmation link.
      Sign up for API Key by visiting the url:
           https://www.themoviedb.org/account/bobthebuilder/request-api?type=developer
                (replace "bobthebuilder" with the username for the account you just created.)
      Click on the "I agree" button.
      Register Your Project - complete the form - for the project url, point them to your repo on github.
      You should now be taken to your profile page, where your key should be visible.
      Complete the TODO:  In flicklist.js, copy and paste this key into the starter code.
  9.  Open the page to confirm it works.
 10.  Commit and Push on Git:
      $ git status
      (should see that you now have unstaged changes; i.e. changes are not staged for commit)
      $ git add --all
      (to stage the changes; --all adds all (both of) the unstaged files, so you don't have to type them one by one.
      $ git status
      (should see the list of files staged for commit)
      $ git commit -m "finish FlickList 0 studio"
      (commits with the -m flag to remind yourself (and others looking at your code) what changes you made during this commit)
      (The convention is to write your commit message using the present tense rather than past tense (e.g. "finish" rather than
      "finished".)
      $ git status
      (should show nothing to commit, working directory clean)
      $ git push origin studio0
      (pushes your changes to your remote repo)
  11.  Revisit https://github.com/YOURUSERNAME/flicklist
      (You should see your new branch up there!)

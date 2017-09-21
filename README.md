# UMBC_HW3  Due 2017-09-XX

## TERRY TODO CHANGE BEFORE POSTING
- [ ] Clone/add remote/push to your own repository
- [ ] Read carefully (my spelling/grammer are terrible, and I'm not spending time to double check)
- [ ] change all hjmjohnson to your class organization or personal github site.
- [ ] I assume your github id is ysyoo.  Fix if necessary.


This homework is designed to introduce you to the git source code management (SCM) system, and the GitHub (www.github.com) web interface front end to the git SCM reponsitory.

You will: 
1. Make an account on github.com (http://www.wikihow.com/Create-an-Account-on-GitHub)
1. Make a new public repo in your new github account called "UMBC_HW3" (see https://help.github.com/articles/create-a-repo/)
1. Invite the user "ysyoo" to contribute to your newly created repository (see https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/ ) .
1. On your local computer, configure git to remember how to give you attribution for your work. (See section "GIT ATTRIBUTION" near the bottom of this page.
1. Clone starting files from my reference repository 
      1. ```bash git clone https://github.com/hjmjohnson.git```
1. Enter the newly downloaded local git repository directory called "UMBC_HW3"
1. Create a new ASCII text file called "MyInformation.txt" (inside the UMBC_HW3 directory).  Use Notepad/vim/emacs/pico/nano/gedit or any other plain ascii text editor. Do not use a word processing application like Microsoft Word.
      1. Add your name to the top line
      1. Add your favorite color to the second line
      1. On the 3rd line, write 2-5 sentences describing why you want to do well in this course.
1. Add and commit the MyInformation.txt file to your *local* git repository
      1. ```bash git add MyInformation.txt```
      1. ```bash git commit -m"DOC:  <<YOUR COMMIT MESSAGE HERE>>"```
1. From within your local UMBC_HW3 directory, create a new alias to your personal repository
      1. ```bash git remote add myrepo https://github.com/{MY_GITHUB_ID}.git```
1. Syncronize your local git repository with your remote github repository
      1. ```bash git push myrepo```
 


GIT ATTRIBUTION
===============

The git commit system imposes a strict attribution policy.  That is to say that every action taken in a git envirionment that changes a repository must be attributed to a particular person.

From a unix command line (Git for Windows provides a unix command line) , you can globally set up the information necessary to set up proper attribution to you for your git actions.  

```bash
% git config --global user.name "First M. Last"
% git config --global user.email "first-last@umbc.edu"
```
Choose your name and e-mail carefully!  These become your unique finger print.  You will need to run these commands on every computer environment that you use (i.e. lab computers, laptop, desktop, your Mom's computer).

Helpful URLS directly relevant to SWD class
--------
- [ ] WIKI Markdown      https://guides.github.com/features/mastering-markdown
- [ ] Java Documentation https://docs.oracle.com/javase/search.html
- [ ] Git For Windows    https://git-for-windows.github.io

Fun :smile: links for in-depth understanding :thumbsup:
--------
- [ ] http://blog.osteele.com/2008/05/my-git-workflow/
- [ ] http://www.lynda.com/Git-training-tutorials/1383-0.html
- [ ] http://www.xkcd.com
- [ ] http://stackoverflow.com
    - [ ] NO CHEATING:exclamation: Provide proper attribution


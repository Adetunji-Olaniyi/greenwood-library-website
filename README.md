# Captone Project: Enhancing a Community Library Website

## Background Scenario

You are part of a development team tasked with enhancing the website for the "Greenwood Community Library". The website aims at be more engaging and informative for its visitors. It currently includes basic section: Home, About US, Events, and Contact US. Your team decided to add a "Book Reviews" section and update the "Events" page to feature upcoming community events.

You will simulate the roles of two contributors: "Morgan" and "Jamie". Morgan will focus on adding the "Book Reviews" section. while "Jamie" will update the "Events" page with new community events.

## Objectives

Practice cloning a repository and working with branches in git.

Gain experince in stagging, commiting, and pushing changes from both developers.

Create pull requests and merge them after resolving any potential conflicts.

## Setup

1. Create a repository on GitHub:

a. Name it greenwood-library-website.
![Createrepository](./img/Create%20repository.png)

b. Initialized it with a README.md file and clone it to my local machine.

![clone](./img/Clone%20repository.png)

![clone](./img/3.Git%20Clone.png)

## Tasks 

In the main branch, using Visual Studio code editor, I will ensure there are files for each of the web pages.

home.html
about_us.html
events.html
contact.html

![Createwebpages](./img/4.Create%20Web%20Pages.png)

2. Add random content into each of the files.

![aboutus](./img/5.aboutus.png)

![contact](./img/6.Contact.png)

![events](./img/7.This%20is%20events%20page.png)

![home](./img/8.This%20is%20home%20page.png)

3. I will stage, commit, and push the changes directly to the main branch.

Git Status

![Gitstatus](./img/9.Git%20status.png)

Git Add

![GitAdd](./img/10.Gitadd.png)

git commit -m "message"

![gitcommit](./img/11.gitcommit.png)

git push

![Gitpush](./img/12.Gitpush.png)

## Morgan's Work: Adding Book Reviews

1. Create a Branch for Morgan:

git checkout -b add-book-reviews

2. Switch to a new branch name add-book-reviews

![addbookreviews](./img/13.Gitcheckout%20addbookreviews.png)

3. Add a new file "book_reviews.html" to represent the book reviews sections:

4. Add a random text content into the file

![bookreviewfile](./img/14.bookreviews.png)

5. Stage, commit, and push chnages with a message "Add book reviews sections."

git status

![gitstatus](./img/15.Gitstatus.png)


git add .

![gitadd](./img/16.Gitadd.png)

git commit -m "message"

![gitcommit](./img/17.Gitcommit.png)

6. Push
git push

![gitpush](./img/18.Gitpush.png)

7. Raise a PR (Pull Request) for Morgan's work

![raisepr](./img/19.Pull%20reguest.png)

8. Merge Morgan's work to the main branch.

![](./img/20.createpullrequest.png)
![merge](./img/20.createpullrequest.png)
![merge](./img/21.%20Merge%20pull%20request.png)
![merged](./img/22.%20merged%20add%20reviews.png)

## Jamie's Work: Update Event Pages
We would repeat the same flow for Jamie's work on Events pages. we would ensure Jamie's work is in "update-events" branch.

Create Jamie's branch

git checkout -b update-events

![gitcheckout](./img/23.Gitcheckoutupdate%20events.png)

git pull origin main

![pushoriginmain](./img/pull%20originmain.png)

Add a new file

![Addnewfile](./img/24.updateeventshtml.png)

Git Status

![gitstatus](./img/25.status.png)

Git Add

![gitadd](./img/26.gitadd.png)

Git commit

![gitcommit](./img/28.Gitcommit.png)

Git Push

![gitpush](./img/29.Gitpush.png)

Jamie's Pull Request

![pullrequest](./img/30.updateeventspullrequest.png)

![](./img/31.createpullrequest.png)

![](./img/32.mergepull%20request.png)


![](./img/33.update%20events%20mergerged.png)

![](./img/34.Merge.png)

End.
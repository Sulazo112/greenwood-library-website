# greenwood-library-website

# Captone Project: Enhancing a Community Library Website

### Bacground Scenario

Been part of a development team tasked with enhancing the website for the "Greenwood Community Library". The website aims at be more engaging and informative for its visitors. Its currently includes basic section: Home, About US, Events, and Contact US. My team decided to add a "Book Reviews" section and update the "Events" page to feature upcoming community events.

I will simulate the roles of two contributors: "Morgan" and "Jamie". Morgan will focus on adding the "Book Reviews" section. while "Jamie" will update the "Events" page with new community events.

## Objectives

Practice cloning a repository and working with branches in git.

Gain experince in stagging, commiting, and pushing changes from both developers.

Create pull requests and merge them after resolving any potential conflicts.

## Setup

Create a repository on GitHub:
Name it greenwood-library-website.

Initialized it with a README.md file and clone it to my local machine.
![Cloning into greenwood-library-website](./img/Cloning%20into%20greenwoon-library-website.png)

## Tasks

In the main branch, using Visual Studio code editor, I will ensure there are files for each of the web pages.

home.html
about_us.html
events.html
contact.html
![File for each of the web page](./img/Files%20for%20each%20of%20the%20web%20page.png)

I will add random content into each of the files.
![Adding random contents into each files](./img/Adding%20random%20contents%20into%20each%20files.png)

I will stage, commit, and push the changes directly to the main branch.

git status
![Git status](./img/Git%20status.png)

git add
![Git add](./img/Git%20add.png)

git commit -m "message"
![Git commit](./img/Git%20Commit.png)

git push
![Git push](./img/Git%20push.png)

## Morgan's Work: Adding Book Reviews

#### I will create a Branch for Morgan

git checkout -b add-book-reviews

Swicth to a new branch name add-book-reviews

Add a new file "book_reviews.html" to represent the book reviews sections:

touch book_review.html

Add a random text content into the file
![Cat book reviews.html](./img/Cat%20book%20reviews.html.png)

Stage, commit, and push changes with a message "Add book reviews sections."

git status

git add .

git commit -m "message"

Push the "add-book-review" branch to GitHub

git push
![Git push origin add-book-reviews](./img/Git%20push%20origin%20add-book-review.png)

Raise a PR (Pull Request) for Morgan's work
![Raise a PR pull request for Morgan](./img/Raise%20a%20PR%20pull%20request%20for%20Morgan.png)

Merge Morgan's work to the main branch.
![Merge book reviews pull request](./img/Merge%20book%20reviews%20pull%20request.png)
![Pull request request merged](./img/Pull%20request%20merged.png)

### Jamie's Work: Update Event Pages

We would repeat the same flow for Jamie's work on Events pages. we would ensure Jamie's work is in "update-events" branch.

#### Create Jamie's branch

git checkout -b update-events

git checkout update-events

Pull request for Jamies

git pull origin main
![Pull request for Jamies](./img/Pull%20request%20for%20Jamies.png)

Update Event.html file using: touch event.html and confirm with vi event,html
![Update event.html file](./img/Update%20event.html.png)

Check Jamie's Status: git status

Jamie's Add: git add .

Jamie's commit: git commit -m ""

Jamie's Push: git push origin update-event
![Git push origin update-events](./img/git%20push%20origin%20update-events.png)



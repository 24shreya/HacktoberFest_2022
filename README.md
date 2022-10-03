<img src="image/Hfest.png">

</br>

# Hacktober Fest 2022
👋🏻 If you're new to Git and GitHub or are looking to get started with open source development, this repository is for you! I want to help you learn about these technologies and participate in Hacktoberfest, so I've collected some resources to get you started.

**Learning Resources**

Name | Resources Link
-----| --------------
Git & GitHub | [Kunal Kushwaha](https://www.youtube.com/watch?v=apGV9Kg7ics)
Markdown | [Eddie Jaoude](https://www.youtube.com/watch?v=OXZ77HvL_Yg)
Git Cheat | [Cheat Code](https://user-images.githubusercontent.com/51878265/165011193-e6157e76-1d6f-45c2-9c95-594d9f9c6163.jpg)

# **RESOURCES FOR BEGINNERS**

### ___INTRO TO OPEN SOURCE___

* DigitalOcean : [INTRODUCTION TO GITHUB AND OPEN-SOURCE PROJECTS](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source)
* GitHub : [HOW TO CONTRIBUTE TO OPEN SOURCE](https://opensource.guide/how-to-contribute/)
* DigitalOcean: [WHAT IS OPEN SOURCE](https://www.digitalocean.com/community/tutorials/what-is-open-source)
* DigitalOcean : [HOW TO USE GIT](https://www.digitalocean.com/community/cheatsheets/how-to-use-git-a-reference-guide)


# **Best Beginner friendly Repostory**

* [First Contributions](https://github.com/firstcontributions/first-contributions)
* [Awesome for beginners](https://github.com/mungell/awesome-for-beginners)
* [Canvas Game](https://github.com/harshit-paneri/canvas-game)
* [Introduction-webpage](https://github.com/Naman-sharma00100/Introduction-webpage)
* [Basic_website_HTML_CSS_only
](https://github.com/Naman-sharma00100/Basic_website_HTML_CSS_only)


## Getting Started 🤩🤗:

- Fork this repo (button on top)
- Clone on your local machine

```
git clone <git repo>
```
- Navigate to project directory.
```
cd filename
```

- Create a new Branch

```markdown
git checkout -b my-new-branch
```
- Add your contribution
```
git add .
```
- Commit your changes.

```markdown
git commit -m "first commit"
```
- Then push 
```
git push origin my-new-branch
```


- Create a new pull request from your forked repository

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream <git repo>
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/master
```
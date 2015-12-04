- title : Introduction to Git
- description : Introduction to Git
- author : Pau Cervera
- theme : black
- transition : default

***

![Git](http://imgs.xkcd.com/comics/git.png)

***

### Menu

---

### First course

* git init
* git add
* git commit

---

### Second course

* git branch
* git merge

---

### Desserts

* git fetch
* git merge
* git pull

***

- data-background : images/firstCourse.jpg

### git init

---

### git add

---

### git commit

***

- data-background : images/secondCourse.jpg

### git branch

---

### git merge

***

- data-background : images/deserts.jpg

### git fetch

---

### git merge

---

### git pull = git fetch + git merge

***
- data-background: images/zen.jpg

### Interlude: The zen of git

---

**Neo** was trying to understand **git** until a kid on
IRC (*who has never been exposed to obsolet VCSs like SVN*) told him:

***
- data-background : images/thereisnospoon.jpg

### There is no spoon

---

And he was enlightened

***

- data-background: images/red-pill.png

### Ready?

***

- data-background: images/cloudchamber2.jpg

### Git Standard Model

---

### Elementary particles

* A **blob** is an object.
* A **tree** is an object.
* A **commit** is an object.

---

### Meta-physics

An **object** is a bunch of bytes with a **sha1**.

---

#### Elementary particles & metaphysics

* A **blob** is a bunch of bytes with a sha1.
* A **tree** is a bunch of bytes with a sha1.
* A **commit** is a bunch of bytes with a sha1.

---

### Interactions

* Any commit has a **parent** which is itself a commit. (Except for
the first one, which is the Big Bang).
* Any commit has a **tree**.
* Any tree is made of **blobs** and possibly other **tree**s.

---

#### At this point, Neo understood that "There is no spoon"


***


***

### References

* [The git parable](http://tom.preston-werner.com/2009/05/19/the-git-parable.html)
* [A Tale of Three Trees](http://www.infoq.com/presentations/A-Tale-of-Three-Trees)
* [Pro Git](http://git-scm.com/book/en/v2)
* [Git magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/)

***

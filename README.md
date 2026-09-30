## Website

https://sandeepvjoshi.github.io/Sandipti

## Git Instructions

* git commit = register my change (it will go to github.com after git push)
* git push = send the change to github.com so it can be published in site
* git pull = get latest from github.com (e.g. if something changed there directly)

### Adding a new file

* git add `<filename>`

### Adding a new folder

You add folder by adding a directory from that folder

* git add `<newfolder>/<newfile>` (or go in that folder and `git add <newfile>`

### Commit

Mark/Register a change for future push.

* git commit -m "<your comment>"

### Push

Push sends all the changes do so far (changes = all commits) to github.com

* git push
(sometimes, if something in github.com has directly changed, git push will give error; in that case do git pull first)

### Periodic Git Activity

* Handy git [cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

Key commands (git bash):

* git add -u <folder> (only add 'modified' files for commit, to avoid accidently adding newly created temporary files)
* git add <folder/file> (to specifically add file or files in folder recursively)
* git commit -m "message"
* git push
* git pull (get latest)

## Markdown cheatsheet

### Headings

Use `#` (one or more)

```markdown
# Heading 1 (hash # in first column) -- in markdown file you should have only one H1 heading
## Heading Level 2
### Heading Level 3
```

### New Lines

You can write on same line or split lines, it will show up all as single line.

E.g.

```markdown
this is a
sample text
```

shows up all in one line:  
this is a
sample text

To add new lines, do any one of the following:

* Add two spaces after the line
* Add a blank line
* Add "<br>"

```markdown
Case 1: Line with two spaces  
...and so this is on new line.

Case 2: A blank line after this

so this is on a new line

Case 3: A br tag after this<br>
...so this is on a new line
```

Case 1: Line with two spaces  
...and so this is on new line.

Case 2: A blank line after this

so this is on a new line

Case 3: A br tag after this<br>
...so this is on a new line

### Bullets

**Important** Make sure to add a blank line before bullets

```markdown
Some text (and then a blank line):

* top level bullet
    * second level bullet (four spaces and *)

1. numbered item (auto numbering)
    1. numbered second level item
1. next item (just writing 1. is fine).
```

The above shows up as:

Some text (and then a blank line):

* top level bullet
    * second level bullet (four spaces and *)

1. numbered item (auto numbering)
    1. numbered second level item
1. next item (just writing 1. is fine).

### Bold Italics

```markdown
This is **bold**, *italics*
```
This is **bold**, *italics*

### Right left justify

```html
<div align="right">right align</div><br>
<div align="left">left align</div> (this should not be needed - default)
```

<div align="right">right align</div><br>
<div align="left">left align</div> (this should not be needed - default)<br>

### Horizontal line

```markdown
---
```

three dashes.

## Site Instructions

### Add new book

Say the new book is kavyaprakasha

* Create folder `contents/sahityashastra/mukhya/kavyaprakasha`
* Create meta.yaml (copy from dhvanyaloka/meta.yaml and edit)
* Done

### Add new chapter

Say adding chapter 2 in da,

* Create new folder `contents/sahityashastra/mukhya/dhvanyaloka/02`
* Copy `meta.yaml` `from dhvanyaloka/01` and edit `title`
* Done

### Adding new section in chapter

Create `.md` file - add `title` and content (add title on top). See other `.md` files.


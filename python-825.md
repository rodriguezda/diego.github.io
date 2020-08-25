# [Python-825](https://github.com/rodriguezda/diego.github.io/blob/master/intropython.md)
🎉🎈🎂🍾🎊🍻💃

A hands on and practical introduction to python programming.



[Slack] | [Diego One-on-One Office Hours](https://calendly.com/rodriguezdiego/python-office-hours) | [Juliann One-on_One Office Hours](https://calendly.com/juliann-mceachern/office-hours) [PSETs] | [PSET Answers]

## Lectures

Tentative schedule. Dates and topics subject to change based on class pace and comfort level.

Lecture | Date | Links 
--- | --- | --- 
1 | August 25th | 🎉 Intro Deck, Tools, Essential Terminology 
2 | August 27th | Basic Data Types, String Formatting
3 | September 1st | Modules, Conditionals
4 | September 3rd | Lists
5 | September 8th | Tuples, Sets, Dictionaries
6 | September 10th | Loops
7 | September 15th | Loops (continued)
8 | September 17th | Functions
9 | September 22nd | Functions practice 
10 | September 24th | Functions review, Classes Introduction
11 | September 29th | Classes 1 Practice / Build Pandas from Scratch Together!
12 | October 1st | Classes 2: Introduction to Inheritance
13 | October 6th | Classes 2: Practice 
14 | October 8th | Build Pandas from Scratch Together!, Foundational Pandas Objects, Accessing Data
15 | October 13th | Final Project Intro, Data Wrangling, Data Cleaning
16 | October 15th | EDA (Exploratory Data Analysis)
17 | October 20th | Titanic Lab Parts 1 & 2
18 | October 22nd | Titanic Lab Parts 2 & 3, Data Vizualizations
19 | October 27th | Final Project: Final Questions, Terminal Commands Deep Dive 
20 | October 29th | Final Presentations!

## Practice Problem Access
A folder containing blank copies of all practice problem sets is in Google Drive.

**Please make a copy of the whole folder and save it to your Drive.**

Please append your name to the name of the folder (e.g. `PYTH225_JohnSmith`). Please share your copy of the folder (with edit access) with your Instructor and your IA.

**This is where you will keep your answers to all the practice problems.**

------

It focuses on improving reading experience with high contrast colors and no fancy effect.

It also uses [Highlight.js](https://highlightjs.org/) for the syntaxic coloration of code snippets.

Demo is available [here](https://dashdashzako.github.io/hugo-journal-demo/).

## Installation

Please refer to the [Hugo documentation](http://gohugo.io/themes/installing/).

## Configuration

A few parameters should be adjusted in the site config:

```toml
[params]
  description = "Blog meta description."
  githubUsername = "your_gh_username"
  twitterUsername = "your_twitter_handle"
  tagline = "Blog tagline. Shown under index title."
[params.work]
  jobTitle = "occupation"
  company = "the company"
  companyUrl = "https://the.company.url/"
[params.gpg]
  key = "0x1111111111111111"
  fingerprint = "0000 0000 0000 0000 0000  0000 0000 0000 0000 0000"
  link = "https://pgp.mit.edu/pks/lookup?op=get&search=0x1111111111111111"
```

### Code highlighting

Both highlight theme and lib can be overridden. Just drop your build in the `static/js` directory, and the theme file in the `static/css` directory.  
Note that the theme has to be named `highlight.css`.

### Customize styles

sass is required to build the theme css file. If [bundler](http://bundler.io/) is installed on your system:

```bash
bundle install

# test your changes
scss-lint scss/journal.scss

# build stylesheet
sass --scss --sourcemap=none scss/journal.scss static/css/journal.css
```

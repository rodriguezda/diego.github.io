# Intro to Python
🎉🎈🎂🍾🎊🍻💃

A hands on and practical introduction to python programming.


[Slack] | [One-on-One Office Hours](https://calendly.com/rodriguezdiego/python-office-hours) | [PSETs] | [PSET Answers]

## Lectures

Tentative schedule. Subject to change based on class pace and comfort level.

Lecture | Date | Links 
--- | --- | --- 
1 | August 25th | 🎉Intro Deck, Tools, Essential Terminology 
2 | August 27th | Basic Data Types, String Formatting
3 | September 1st | 283 
4 | September 3rd | 283 
5 | September 8th | 283 
6 | September 10th | 283 
7 | September 15th | 283 
8 | September 17th | 283 
9 | September 22nd | 283 
10 | September 24th | 283 
11 | September 29th | 283 
12 | October 1st | 283 
13 | October 6th | 283 
14 | October 8th | 283 
15 | October 13th | 283 
16 | October 15th | 283 
17 | October 20th | 283 
18 | October 22nd | 283 
19 | October 27th | 283 
20 | October 29th | 283 




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

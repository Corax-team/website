# Contributing

**IMPORTANT: Please read this entire file, even if some things do not apply to your change.**

So you want to contribute to the website. Thats great! It is absolutely an advantage to know a bit about jekyll before you start.

## Style guide

### Formatting

Before a file is committed, please use `Prettier` to format your SCSS file.
This is done to maintain consistency between files and commits.

### Files

For some files, certain rules apply. These will be specified here.

#### SCSS

If you are making a new SCSS file, the first three lines are required to be this:

```txt
---
#// Front matter comment to ensure Jekyll properly reads file.
---
```

If the three first lines do not match this, your pull request will be denied.

#### HTML

If you are making a new SCSS file, the first lines are required to be these:

```txt
---
layout: <the layout of your page, usually default>
css-file: <the scss file that will be used for this page. please only include the filename, extensions will be added by the renderer at a later stage>
---
```

## Commit messages

When you commit your changes, please use infinitive form for your commit messages. For example: `Add a new file` or `Fix misspelling`. The commit description should be a more descriptive description of your changes. For example: `Added a new file for a language` or `Fixed misspelling of "language"`.

If your commit simply contains formatting, please prepend your commit message with `[skip ci]`

## Pull request descriptions

Please use the provided formats for describing your issue.

layout: post
title: "Multiple GitHub PR Templates"
date: 2022-08-23 13:21:00 -0000
categories: github

1. For a single pull request template, you can simply add a file named `pull_request_template.md`
1. If you want to use multiple PR templates, you can create `.github/PULL_REQUEST_TEMPLATE` folder and add markdown files such as `bug.md` inside that folder.
1. To apply `bug.md` PR template in `PULL_REQUEST_TEMPLATE` folder, you need to add `?template=bug.md` to the end of your pull request URLs.

Similarly, if you want to add GitHub issue templates, you can add `.github/ISSUE_TEMPLATE` folder and add markdown files in that directory.
To apply issue templates, add `?template=bugs.md` to the end of the issue URL.

---
layout: workbook
title: ワークブック・GitHubの基本
description: This student and teacher workbook will be your companion to the GitHub Foundations class taught by the GitHub Training Team and other educational groups. In this course, you'll learn basic collaboration skills towards a productive use of Git and GitHub in your open source work and daily job assignments.


---

## バージョン管理のコンセプト

### 概要
* Gitとは、情報の追跡ツール
* GitHubとは、コラボレーションプラットフォーム
* 分散バージョン管理
* [Git略史](http://git-scm.com/book/ja/%E4%BD%BF%E3%81%84%E5%A7%8B%E3%82%81%E3%82%8B-Git%E7%95%A5%E5%8F%B2)
* [Gitプロジェクトホームページ](http://git-scm.com)

### 詳細
Gitとは、2005年にリーナス・トーバルズによって開発された__オープンソースの分散__バージョン管理システムです。Gitはリナックスのカーネルのバージョン管理に使われ、いくつかの調査によると、もっとも人気のあるモダンなバージョン管理システムです。

Git is the open source, command line tool that forms a part of the workflows we'll cover in this course.  It has been called the successor to CVS and Subversion by many users, and maintains some similarity in behavior to these historical open source version control tools.

Maintaining a current version of Git is important. While you'll accurately hear that Git is generously backwards-compatible, the latest versions offer error message enhancements, performance tunings, and usability features that make using Git ever more quick and pleasant.

Verifying that Git is installed and operational can be done by requesting Git to display its current version using this command:

``` shell
$ git --version

git version 1.8.2
```

##  GitHub Installers
* [GitHub for Windows installer](http://windows.github.com)
* [GitHub for Mac installer](http://mac.github.com)
* [Pro Git Book: Installing Git](http://git-scm.com/book/en/Getting-Started-Installing-Git)
* **Windows**: The GitHub for Windows installer can be found at http://windows.github.com.
* **Mac**: The GitHub for Mac installer can be found at http://mac.github.com.
* **Linux**: Git's source code and a listing of supported package managers can be found at http://git-scm.com/download/linux.

### Details
The command line version of Git has a very light footprint. For most platforms, you can simply copy the binaries to a folder that is on the executable search $PATH. Git is primarily written in C, which means there is a unique installer for each operating system.


## The GitHub platform
* [GitHub.com feature list](https://github.com/features)
* [How to sign up for GitHub](https://www.youtube.com/watch?v=ezxRcdJ8glM&list=PLg7s6cbtAD17rhrz2BJWAPJMjR71B3IDx)

### Details
GitHub accounts are free. Sign up for one at [github.com/join](https://github.com/join).

GitHub is the repository hosting, collaboration, deployment, and distribution platform for both open source and private software projects.  It facilitates discussing changes-in-progress through the concepts of Issues and Pull Requests and provides a web user interface to much of Git. The web flow made possible by GitHub brings a much wider range of contributors, including documentation specialists, designers, and ops engineers into the flow of contributing to your application's life cycle.

GitHub accounts are free for an unlimited quantity of public repositories. Only private repositories cost to host on the service. Private repositories are typically used for closed-source consulting client or corporate products, whereas public repositories are typically used for open source.

Sign up for a free GitHub account at https://github.com/join.

Git can be installed as a unified GitHub GUI and command line or merely as a stand-alone command line interface.


## Interacting with repositories

### Summary
* [GitHub web flow](https://guides.github.com/overviews/flow/)
* GitHub GUIs for Mac, Windows
* Command line

## Getting to know Git & GitHub

### Summary
* Repository initialization
  * New project and new repository
  * Repository based on existing content
  * Through web interface
  * Web interface and GUI client

## Acquiring repos

### Summary
* Clone from web (Clone in Desktop button)
* Clone via personal repo list in GitHub Desktop
* Complete "copy" explanation

## Version control basics

### Summary
* Commits
  * History marker for file(s), change(s)
  * Record of author, time, and message
* Branches
  * Container for grouped commits
  * Simpler means to integrate change
  * Cleaner code review possibilities
* GitHub, local repositories

## GitHub repository interaction

### Summary
* Commits (GitHub.com)
  * Actionable steps (Create, Edit, Remove, Move)
  * Commit messages
  * Listing page on GitHub
* Branches (GitHub.com)
  * Selection menu
  * Listing page
  * Comparison view

## Local repository interaction

### Summary
* Changes (with text editor)
* Comparison (diff via GHfD)
* Commits
* Branches
* History
* Syncing (GHfD)

* Commits (GitHub for Desktop)
  * Managing file on system, reviewing results
  * Line-level tracking
  * Grouping files
  * Synchronizing local commits
* Branches (GitHub for Desktop)
  * Create
  * Change
  * Publish

## GitHub workflows

### Summary
* Forking
    * [Guide to Forking](https://guides.github.com/overviews/forking/)
    * Reason for forks
    * What it encourages
    * How it insulates
    * Keeping up to date (too advanced?)
    * Original (base) and Fork (individual copy)
* The GitHub Flow
    * Branch
    * Commit
    * Compare
    * Pull Request
    * Discuss
    * Animated GIF
    * Line by line code review conversation
    * Clone locally with GHfD (optional)

## GitHub visualizations

### Summary
* Comparing/Diff-ing
  * Code
  * Prose
  * Images
  * Maps
  * Spreadsheets
  * 3D models
* Branch view
* Branch ahead/behind positions
* Network graph
* Activity graph

## GitHub Wikis

### Summary
* Fast documentation authoring for repositories
* Standalone repository
* Easy access from repository navigation

## GitHub Pages

### Summary
* Web page for your repository
* Web page for your account
* Author, edit, launch from GitHub

## GitHub Features

### Summary
* Notifications
* Watching repositories
* Starring repositories
* Gist
* GitHub Flavored Markdown
  * Basics
  * Emoji
  * Checklists (Issues, Gists)

## GitHub shortcuts

### Summary

* `/` command bar
* `?` help
* `t` fuzzy file search

## Project management basics

### Summary
* GitHub Issues
* Milestones
* Network
* Pulse
* Tags, Releases
* Collaborators
* Organizations
* Teams

## Special Repository Features of GitHub
* Contributing.md
* License.md
  * During repository creation
  * `+` a file with existing repository (special dropdown)
* .gitignore
  * During repository creation
  * `+` a file with existing repository (special dropdown)
* Readme.md
  * In root
  * In subfolders

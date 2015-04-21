# ROSSConf

This repository is a place to organize some thoughts and
issues in order to prepare for ROSSConf in Vienna,
April 25, 2015.

This repository will contain issues that explain high-level goals, and
break these down into bite-sized chunks of work. The issues here will
link to all the necessary repositories and issues, so you shouldn't
have to try to wrap your head around the entire exercism.io ecosystem.

## About Exercism

Exercism is a site for practicing small programming problems, and
for improving your programming skills through conversations about the
solutions to these programming problems.

There are two components: a command-line application that lets you pull down
exercises and submit your solutions, and a website where the conversations
happen.

### Technical Stack

The website and various APIs are written in Ruby (Sinatra), with HTML, CSS,
and JavaScript on the frontend.

The CLI is written in Go.

The exercises for each language track lives in its own repository, so that Haskell
developers don't need to bother with Ruby (etc).

The API that serves up the exercises, a.k.a. "x-api", a.k.a. the "Problems API"
[includes all of the language-specific](https://github.com/exercism/x-api/tree/master/problems)
repositories as git submodules.

### Overview of Problems

The most important thing that we need to get right with exercism is the conversation.
Everyone should get feedback on their code, they should get it quickly, and the feedback
should be high quality.

There are many things that are preventing this from happening, and at the moment the biggest
one is probably that it's so hard to understand what exercism is about when you come to the
site. It's confusing, it's unclear how the process works, how you can get started, and what
to expect.

Issues #1 through #6 are all about making it easier to get people started on the site.

## Claiming Work

If you choose to work on a part of an issue, please add a comment to that issue
saying what you're going to tackle, that way we can avoid having several people
submit pull requests for the same thing.

## TODO

- high-level problems / core focus
- roadmap
- types of contributions (including skillsets and skill levels)

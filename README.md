# ROSSConf

This repository is a place to organize some thoughts and
issues in order to prepare for ROSSConf in Vienna,
April 25, 2015.

This repository will contain issues that explain high-level goals, and
break these down into bite-sized chunks of work. The issues here will
link to all the necessary repositories or issues or information, so you
shouldn't have to try to wrap your head around the entire exercism.io
ecosystem.

## About Exercism

Exercism is a site for practicing small programming problems, and
for improving your programming skills through conversations about the
solutions to these programming problems.

There are two components: a command-line application that lets you pull down
exercises and submit your solutions, and a website where the conversations
happen.

The website and various APIs are written in Ruby (Sinatra), with HTML, CSS,
and JavaScript on the frontend.

The CLI is written in Go.

In addition, the exercises for each language track lives in its own repository.

The API that serves up the exercises, a.k.a. "x-api", a.k.a. the "Problems API"
includes all of the language-specific repositories as git submodules.


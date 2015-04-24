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

#### Improve the Conversation

The most important thing that we need to get right with exercism is the conversation.
Everyone should get feedback on their code, they should get it quickly, and the feedback
should be high quality.

There are many things that are preventing this from happening, and at the moment the biggest
one is probably that it's so hard to understand what exercism is about when you come to the
site. It's confusing, it's unclear how the process works, how you can get started, and what
to expect.

#### Improve the Problems/Tracks

Another important part of exercism is the practice problems themselves. The problems themselves
can be improved, as can the workflow around maintaining them.

There are several new language tracks in the works, and if your favorite language isn't on the
list, that's an easy fix.

Also, there are some suggestions with regards to making it easier to maintain languages and keep
them in sync.

#### General Fixes

Check out the [bug](https://github.com/exercism/exercism.io/labels/bug) and
[size/small](https://github.com/exercism/exercism.io/labels/size%2Fsmall)
labels for miscellaneous issues. If there's not enough context to fix the
problem, it would be incredibly helpful if you posted clarifying questions.

## Claiming Work

If you choose to work on a part of an issue, please add a comment to that issue
saying what you're going to tackle, that way we can avoid having several people
submit pull requests for the same thing.

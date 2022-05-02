# GitHub Training

## THE GITHUB WORKFLOW
This is the workflow I recommend you use when you want to contribute to projects on github.
    1. Fork a project on github.
    2. Clone your github fork to your computer
    3. create a topic branch for your own work in your local clone
    4. commit changes to your local repository
    5. push the changes to your github fork
    6. send a pull request back to the original project
These are the basic things that you need to understand, and I will go through all of the terminology above and a little bit more. I will not show you how to do it, but rather explain what these things mean, so that afterwards you can use which ever tool makes the most sense to you.

## CENTRALIZED VS DISTRIBUTED VERSION CONTROL
Git is a distributed version control system, as a contrast to for example subversion that is centralized. What this means is that with subversion, the code repository (repo) lives on a server and people need special permissions (commit rights) to be able to add code to the repo. Everything lives in one place.

Centralized version control
In a distributed system, you get a repository of your own when you clone the project. This means you can work and add code to the repo even when offline, since the repository lives on your computer. But this also means you need a bit of discipline in keeping in sync with the rest of development, since your repository is separate from the others.


Distributed version control

## FORK AND CLONE
First of all, we need to fork. In github, all you need to do is click that fork button and you get your own personal repository of Thematic copied to your github user account.

When you want to actually work on your repository you need to clone it to your computer, and now you own two repositories: one remote on github and one local on your computer.

It’s called forking on github because every repository is a potential for taking development in your own direction. The choice to contribute back to the original project is yours to make, but of course you want to do that — that’s why you are reading this article, right?


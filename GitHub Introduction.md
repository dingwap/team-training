# GitHub Training

## GitHub Workflow
Recommended workflow when you want to contribute to projects on github.
    1. Fork a project on github.
    2. Clone your github fork to your computer
    3. Create a topic branch for your own work in your local clone
    4. Commit changes to your local repository
    5. Push the changes to your github fork
    6. Send a pull request back to the original project
    
These are the basic things to understand, the terminology above will be explained in more detail below.

## Explaining centralised and distributed version control
Git is a distributed version control system, which is different to a traditional centralised model. With a traditional centralised model the code repository (repo) is held on a server and contributors need commit rights to be able to add content to the repo. Everything is held in one place.

**Centralized version control**
<image>

With a distributed system, a contributor gets a repository when you clone a project. This allows you to work and add code to the repo locally on your device, and when offline, as a copy the repository lives on your computer. But this also requires a process for keeping content in sync with the main repository, since your local repository is separate.

**Distributed version control**
<image>
    
## Forking and Cloning a repository
To get startedm we need to fork the repository which contains the content you want to work on and constribute to. In github, you can use the *fork* button to create your own personal repository within your github account.

When you want to actually work on the repository you need to clone it to your computer, which creates two repositories, one remote on the github website (viewed via your browser) and one local on your computer (viewed and edited using local tools).

The process is referred to as forking on GitHub as every repository which is forked provides the potential for taking development in your own direction within your own repository, or contributed back to the original project. We will be covering contributing back to the main project within this documentation rather than creating and maintaining separate, forked content.


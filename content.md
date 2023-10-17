# Sinatra Template

We have a number of template repositories prepared in our `appdev-projects` GitHub organization for you to use.

This lesson details the `sinatra-template` and how to make use of it to work on your own side projects.

Find the template at this link:

[github.com/appdev-projects/sinatra-template](https://github.com/appdev-projects/sinatra-template)

## Create repository from template

As opposed to the graded class projects, which you will begin by clicking a "Load [assignment]" button and forking, for our template repositories, you will manually create your own blank app. 

- Once you have signed in to GitHub, visit the template of your choosing (e.g. [appdev-projects/sinatra-template](https://github.com/appdev-projects/sinatra-template)) and click the "Use this template" button, and select "Create a new repository" from the dropdown:

<!-- ![](/assets/gh-pages-template-1.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686161492/gh-pages-template-1_tlxhbl.png)
{: .bleed-full }

- On the next screen, leave the "Owner" dropdown alone, it should be set to _your_ GitHub username.
- For "Repository name", enter any name you would like for your new project. **You should choose a unique, memorable name for the repository. It does not have to match the template name.**
- Make sure the "Public" option is selected. 
- Click "Create repository from template".

<!-- ![](/assets/gh-pages-template-2.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686166582/gh-pages-template-2_rvvdb4.png)
{: .bleed-full }

After a moment you will be brought to the new page at `github.com/<your-username>/<name-you-chose>`, with a copy of all the code from that template. You can get to work right away in a new codespace. Be patient, it will take about two full minutes to fully prepare, but subsequent boots of the codespace will be much faster from [your `github.com/codespaces` dashboard](https://github.com/codespaces).

<aside markdown="1">
You can also work on any project on [Gitpod](https://learn.firstdraft.com/lessons/48-gitpod-setup), or in a [local setup](https://learn.firstdraft.com/lessons/49-local-setup), but we recommend sticking with codespaces as your development environment for now.
</aside>

### This is not a fork

**This is not a fork, this is a newly generated codebase from a template repository.**

What does that mean for us practically?

* Just like a fork, the template generated repo contains a snapshot of all of the code in the repository you generated the template from.
* The template generated code is not tied to the upstream forked repository, meaning that changes to the upstream fork (i.e. commits) cannot be easily fetched into the new codebase.
* Creating codespaces from the template generated repo [will use your free monthly Codespace hours](#a-note-about-codespace-hours){: target="_self"}.
* Template generated code is not graded, so `rake grade` won't be necessary. The templates are just there for you to have fun with and build your own apps!

### A note about codespace hours

When you generate a repository from a template, rather than forking it in the case of the graded projects, the codespaces hours that you use will be billed to **your personal account rather than the `appdev-projects` organization**. But fear not, all GitHub accounts have 60 free codespace hours per month included.

<aside markdown="1">
Technically, all GitHub accounts have 120 free CPU hours (or 180 for Pro accounts) on Codespaces. By default, a new codespace is generated on a 2-core machine (2 CPUs), hence 120 core hours ➗ 2 cores = 60 hours. You can [increase the number of cores](https://learn.firstdraft.com/lessons/47-codespaces-setup#increasing-cores-on-a-codespace), but beware of that eating into your free hours significantly.
</aside>

You can also apply for education benefits on [education.github.com](https://education.github.com/discount_requests/application). Just select "Student" and ideally use a `.edu` email address associated with your school. After a processing period, your account will be upgraded to a free GitHub Pro account, which includes 90 free codespace hours!

Likely, the 60 (or 90) free monthly codespace hours will be sufficient for you to work on side projects, as the majority of time spent coding will be on graded forks of non-template projects.

If you're ever unsure of who is paying for the codespace hours in a given repository, just have a look at the note in the "Code" dropdown menu when you create a new codespace:

---

<!-- ![](/assets/who-pays-for-codespace.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686181395/who-pays-for-codespace_rtvrwn.png)

## Sinatra Template

As we transitioned from HTML to coding in Ruby, we slowly built up a dynamic web app beginning from the bare-bones `appdev-projects/ruby-template` with various Ruby files that we iteratively added. Eventually, we had many files that were wired together using the lightweight Sinatra framework, which is like a lean version of Rails.

If you want to build your own apps using that Sinatra framework, then we have prepared a template repository at:

- [appdev-projects/sinatra-template](https://github.com/appdev-projects/sinatra-template)

In this case, we aren’t hiding any files from you in the VSCode explorer window, [as we did in the HTML projects](https://learn.firstdraft.com/lessons/220-html-template#hidden-files). It’s time to get used to seeing a whole lot of files, because this is nothing compared to the Rails infrastructure!

If you want to deploy an app based on the Sinatra template, see [the instructions for Render deployment](https://learn.firstdraft.com/lessons/114-deploying-to-render).

---

See more on my site: https://www.drewkhoury.com/tags/devops/

# devops-101

These websites shaped my understanding and thoughts of the industry:

- https://martinfowler.com/articles/developer-effectiveness.html
  - and thus `Accelerate` and the `State of DevOps report`
- https://martinfowler.com/delivery.html
  - and thus `Extreme Programming`, `Continuous Integration` and related topics
- https://trunkbaseddevelopment.com/
- https://web.devopstopologies.com/
- https://cloud.google.com/architecture/devops/capabilities
  - a broad range of topics around version control, trunk-based development, CI, deployment automation, testing, delivery, test data management, shifting-left on security ...  very detailed and well put together
- [Agile Product Ownership in a Nutshell video](https://www.youtube.com/watch?v=502ILHjX9EE)

## Definitions
- [DevOps defined by wikipedia](https://en.wikipedia.org/wiki/DevOps)
- [DevOps defined by AWS](https://aws.amazon.com/devops/what-is-devops/)
- [DevOps defined by Atlassian](https://www.atlassian.com/devops)
- [DevOps defined by SAFe](http://www.scaledagileframework.com/devops/)

## Frameworks

- [DevOps Bookmarks](http://www.devopsbookmarks.com/) - There are new awesome tools and frameworks being released everyday. This is an open and transparent attempt at aggregating all those.

## Lists

- [AcalephStorage :: Awesome DevOps](https://github.com/AcalephStorage/awesome-devops) - A curated list of resources for Devops
- [joubertredrat :: Awesome DevOps](https://github.com/joubertredrat/awesome-devops) - This is the awesome list with all open source and free applications that you can use in your management.
- [Awesome SysAdmin](https://github.com/kahun/awesome-sysadmin) - A curated list of amazingly awesome open source sysadmin resources inspired by Awesome PHP.

## Misc
- [How to annoy a web developer](https://github.com/omidfi/how-to-annoy-a-web-developer/blob/master/README.md) - A list of tips on How to annoy web developers, hopefully for knowing and avoiding them.
- [DevOps Types and Anti-Types](http://web.devopstopologies.com/)
- [Atlassian Toolchain](https://www.atlassian.com/blog/devops/how-to-choose-devops-tools)
- [GitHub DevOps Tools Showcase](https://github.com/showcases/devops-tools)
- [gitflow](http://nvie.com/posts/a-successful-git-branching-model/)
- [DevOps Checklist](http://devopschecklist.com/)
- [15 Point Checklist](https://medium.com/devopslinks/the-15-point-devops-check-list-8cd2afb4a448)
- [The Must Know Checklist For DevOps & Site Reliability Engineers
](https://hackernoon.com/the-must-know-checklist-for-devops-system-reliability-engineers-f74c1cbf259d)
- [xebialabs periodic-table-of-devops-tools](https://xebialabs.com/periodic-table-of-devops-tools/)
- [xebialabs - release and deployment pipeline](https://xebialabs.com/solutions/devops/)
- [Why the Best Companies and Developers Give Away Almost Everything They Do
](http://blog.ycombinator.com/why-the-best-give-away/)
- [The twelve-factor App](https://12factor.net/)

## Communities

- [DevOps Forum](https://devops-forum.slack.com)


## Technology

Interactive "Playgrounds" in your browser: https://www.katacoda.com/

### Containers

Containers are an amazing innovation that have many every day uses. They can be used locally, in your build servers, for development and production deployments. You can also use them to test new services and keep your laptop free of clutter!
How to build, test and deploy modern code in a repeatable fashion: https://3musketeers.io/

#### Docker

- https://en.m.wikipedia.org/wiki/Docker_(software)
- https://www.katacoda.com/courses/docker/

#### Kubernetes (k8s)

Intros:

- https://en.m.wikipedia.org/wiki/Kubernetes
- https://danlebrero.com/2018/07/09/kubernetes-explained-in-pictures-the-theme-park-analogy/
- https://youtu.be/Q4W8Z-D-gcQ
- https://youtu.be/R9-SOzep73w

k8s documentation:

- https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/
- https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/
- https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/
- https://kubernetes.io/docs/concepts/configuration/configmap/
- https://kubernetes.io/docs/reference/kubectl/cheatsheet/#interacting-with-running-pods


learn k8s interactivly:

- https://www.katacoda.com/courses/kubernetes
- https://www.katacoda.com/courses/kubernetes/playground
- https://katacoda.com/contino

more k8s:

- https://cloud.google.com/blog/products/gcp/kubernetes-best-practices-organizing-with-namespaces
- https://github.com/ramitsurana/awesome-kubernetes
- https://stripe.com/blog/operating-kubernetes

**request and limits:**

https://jaxenter.com/manage-container-resource-kubernetes-141977.html

A request is the amount of that resources that the system will guarantee for the container, and Kubernetes will use this value to decide on which node to place the pod.

A limit is the maximum amount of resources that Kubernetes will allow the container to use.

In the case that request is not set for a container, it defaults to limit.

If limit is not set, then if defaults to 0 (unbounded).

Setting request < limits allows some over-subscription of resources as long as there is spare capacity. This is part of the intelligence built into the Kubernetes scheduler.

![request-and-limit](https://jaxenter.com/wp-content/uploads/2018/03/container-resource-1.png "request-and-limit")

### Cloud

- https://infrastructure.aws/
- https://www.awsgeek.com/
- https://docs.microsoft.com/en-us/azure/architecture/aws-professional/ - This article helps Amazon Web Services (AWS) experts understand the basics of Microsoft Azure accounts, platform, and services. It also covers key similarities and differences between the AWS and Azure platforms.

#### IaC / Terraform

- https://terraform-cheatsheet.uk/
- https://github.com/contino/tc-vpc
- https://github.com/docnetwork/Infra-as-code-challenge

### Markdown

- https://guides.github.com/features/mastering-markdown/

### Git

- Git basics: https://git-scm.com/book/en/v1/Getting-Started-Git-Basics
- Super Simple git demo: https://rogerdudler.github.io/git-guide/
- https://help.github.com/en - Lots of articles/guides to explore
- Visual guide to git: http://marklodato.github.io/visual-git-guide/index-en.html
- https://try.github.io/ - Interactive guides
- https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/ - Guide guide with pictures and commands via a step by step guide
- https://guides.github.com/introduction/git-handbook/ - Git/Github guide
- https://books.goalkicker.com/GitBook/ (The Git® Notes for Professionals book is compiled from Stack Overflow Documentation, the content is written by the beautiful people at Stack Overflow.)

Cheatsheets:

- https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf
- https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
- https://about.gitlab.com/images/press/git-cheat-sheet.pdf (includes diagrams)

**Branching:**

Choosing a branching strategy will be something personal to your team and tailored your team's maturity.

Consdier: trunk based dev > github flow > gitlab flow > anything else

- https://trunkbaseddevelopment.com/ - Trunk
- https://guides.github.com/introduction/flow/ - Github flow
- https://docs.gitlab.com/ee/workflow/gitlab_flow.html - Gitlab flow

Other info: 

- https://nvie.com/posts/a-successful-git-branching-model/ - Popular (but now quite old) branching model
- https://www.nebbiatech.com/2019/03/15/git-branching-strategies-which-one-should-i-pick/ - compare branching
- https://www.slideshare.net/BosniaAgile/managing-software-product-versioning-with-gitflow-vsts-and-atlassian-sourcetree
- https://www.endoflineblog.com/gitflow-considered-harmful

### Ansible

Interactive "Playground" in your browser: https://www.katacoda.com/courses/ansible/

https://docs.google.com/presentation/d/1jIsDHf-5M1w_KWAyU_R5Uv-iHwvRntUb4cC3yBW3_ME/ - Ansible 101 Presentation

http://docs.ansible.com/ansible/latest/index.html - Ansible Documentation
http://docs.ansible.com/ansible/latest/modules_by_category.html - Module categories
http://docs.ansible.com/ansible/latest/list_of_all_modules.html - All Ansible Modules
http://docs.ansible.com/ansible/latest/YAMLSyntax.html - YAML Syntax ... read this a few times, it'll come in handy
http://docs.ansible.com/ansible/latest/playbooks.html - Ansible Playbooks

https://zaiste.net/posts/ansible_101/ - A nice 5 minute hands-on intro to Ansible

https://medium.com/@denot/ansible-101-d6dc9f86df0a - 10 Min Ansible overview/intro

https://gist.github.com/andreicristianpetcu/b892338de279af9dac067891579cad7d - Ansible cheatsheet, a great reference point for just about any bit of Ansible code you'd need to write

https://www.ansible.com/blog/ansible-best-practices-essentials - Best practices

https://serversforhackers.com/c/an-ansible2-tutorial - Detailed Ansible tutorial with explaination and code.

https://gist.github.com/phred/2897937 - pedantically commented playbook

# agile 101

## Materials for POs

### PO Basics

* [Agile Product Ownership in a Nutshell video](https://www.youtube.com/watch?v=502ILHjX9EE)
* [Agile Manifesto](https://agilemanifesto.org/)
* [The 2020 Scrum Guide](https://scrumguides.org/scrum-guide.html)
    * This is a basic overview of Scrum
    * Scrum is an agile framework for software development teams to organize themselves
* [Scrum roles and job titles in scrum](https://www.atlassian.com/agile/scrum/roles)
* Scrum vs Kanban
    * <https://www.atlassian.com/agile/kanban/kanban-vs-scrum>
    * [Scrum vs Kanban image](https://miro.medium.com/max/4766/1*cTEkZOm4GHSPh9JBt6iLZQ.png)

### PO Advanced

* [Product Management Overview](https://www.atlassian.com/agile/product-management)

### Ceremonies

These are the regular meetings which are established in the Scrum Guide

* [Sprint Planning](https://scrumguides.org/scrum-guide.html#sprint-planning)
* [Standup](https://scrumguides.org/scrum-guide.html#daily-scrum)
* [Sprint Review](https://scrumguides.org/scrum-guide.html#sprint-review)
* [Retrospective](https://scrumguides.org/scrum-guide.html#sprint-retrospective)

# Enablement Material
> Red Hat Open Innovation Labs Enablement Material. 

![jenkins-crio-ocp-star-wars-kubes](./images/jenkins-crio-ocp-star-wars-kubes.png)

This is a collection of practices and exercises to take a learner through a four day simulated residency experience. Learners can expect to be exposed to labs practices such as [Event Storming](https://rht-labs.github.io/practice-library/practices/event-storming/), [Social Contract](https://rht-labs.github.io/practice-library/practices/social-contract/) and [Impact Mapping](https://rht-labs.github.io/practice-library/practices/impact-mapping/) amoung many more which can be found in our [Practice Library](https://rht-labs.github.io/practice-library/). Learners will also be exposed to `Labs CI/CD` - how we use OpenShift & Ansible in conjunction with Jenkins to automate build and deploy of a sample todolist application and it's required infrastructure.

## Learner pre-requisites
 - OCP CLI v3.9
 - Ansible v2.5
 - NodeJS v8.x
 - Git Installed
 - Google Chrome Web Browser (>59)
 - Docker latest
 - Access to an OpenShift cluster `oc login -u <username> -p <password> <cluster_url>`
 - Text editor such as Atom, IntelliJ or Visual Studio Code (The exercise were created using VSCode, so the screenshots will match it's layout and colour schemes)

> (TODO) Download the tools-container containing required Ansible and OpenShift tooling pre-installed

______

## Setup your IDE
If you are using VSCode; some handy plugins that will make the lessons easier are:
 - YAML Syntax Highlighter
 - Autosave 
 - JavaScript Syntax Highlighter
 - Vue.js
 - Eslint

______

## Command-line cheat sheet

### Directories

1. View the current directory
```
pwd
```
```
/home/my_user
```

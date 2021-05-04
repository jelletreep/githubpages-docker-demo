# Git version control for Utrecht University

1. Getting started
2. Usage
3. Learning Git
4. Best practices
5. Cool projects


## 1. Getting Started
### First time connecting to the Utrecht University Github Organization

To be able to use the Utrecht University Github Organization

You need to be a UU Employee AND
You need a personal Github account

1. First time connection: Click [here](https://github.com/orgs/UtrechtUniversity/sso) and authenticate using your solis ID. This will make you a member of the organization and gives you permissions to create repositories and teams.
2. Go to [https://github.com/UtrechtUniversity](https://github.com/UtrechtUniversity) and start working. 
3. The next time you can go straight to [https://github.com/UtrechtUniversity](https://github.com/UtrechtUniversity), now you will see a green button with Single Sign-on

## 2. Usage
#### Code not data
  This Github organization is meant for managing software and not a data repository. See this [link](https://www.uu.nl/en/research/research-data-management/tools-services/tools-for-storing-and-managing-data/storage-solutions) for data storage solutions. If you are a novice make sure to learn the basics of Git version control first in order to manage your projects in a secure way.  

#### Sensitivity
  The Suitability level for this Github organization can be found in the Service Description (link)

#### Creating Repositories
As soon as you have authenticated with solisID using the steps outlined above you will have permission to create Repositories in the [UU github organization](https://github.com/UtrechtUniversity). View [Github Documentation](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository) for instructions on how to create a repository.

#### Creating Teams
As soon as you have authenticated with solisID using the steps outlined above you will have permission to create teams in the [UU github organization](https://github.com/UtrechtUniversity). View [Github Documentation](https://docs.github.com/en/organizations/organizing-members-into-teams) for instructions on how to create a team.

#### Inviting colleagues
When you create a repository or team, you will automatically have permission to invite collaborators. When you [invite](https://docs.github.com/en/organizations/organizing-members-into-teams/adding-organization-members-to-a-team) a UU colleague to a team they will automatically receive an invitation to join the UU github organization. When you want to invite a UU colleague to a repository without using github teams, the colleague should first become a member of the organization via the Getting Started steps above. When your colleague is a member you can invite your colleague to collaborate on repositories. 

#### Inviting external collaborators
Non-UU collaborators or UU students can be invited as outside collaborator to repositories [Github Documentation](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/adding-outside-collaborators-to-repositories-in-your-organization).

#### Command line access
When you use the command line (terminal or Git Bash) to interact with Github it is also important to at least 1 time authenticate via [Single Sign-on](https://github.com/orgs/UtrechtUniversity/sso). From the command line you will probably make use of an SSH key or a Personal Access Token. These keys have to be authorized to be used for the github organization UtrechtUniversity. See the following instructions:

- SSH access
  [Creating an SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
  [Authorizing SSH key for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-an-ssh-key-for-use-with-saml-single-sign-on)
- PAT access
  [Authorizing Personal Access Token for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)

#### Github actions limits
Github Actions minutes and storage are unlimited for public repositories. Whenever possible use public repositories if you are using Github Actions. There are monthly limits for using Github actions in private repos on an organization level. **If this limit is reached Github action minutes will be disabled for private repos for the remaining part of the month**.

#### Github apps and Third party access
The following applications are authorized in the Organization:
- Zenodo
- Codecov
- Microsoft Teams
- Slack
- Travis CI

For other applications, submit a request via Topdesk.



## 3. Learning Git
Using Git version control is key in the Open Science paradigm and helps managing versions of files, collaboration and publication.
A git novice should invest some time to get acquainted with the way of working. Typically a one day course will get you started.

Resources:  
[Software carpentries course documentation](http://swcarpentry.github.io/git-novice/)  
Course calendar


## 4. Best practices
#### Open Science FAIR software
  - https://fair-software.nl/
  - https://www.uu.nl/onderzoek/open-science/themas/fair-data-en-software
#### Managing your github projects 
  - Set repository visibility to public as early as possible
  - Use a project template to automatically create a folder structure (e.g. [this one](https://github.com/UtrechtUniversity/rse-project-templates/tree/master/good-enough-project))
  - Use [Github Pages](https://pages.github.com/) to publish a project overview and link to all relevant repositories and collaborators
  - Use [topics](https://github.com/topics) to increase findability
  - Working with [Github teams](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams) to organize your projects and create a central location for team discussions and repositories. 
 
## 5. Cool projects






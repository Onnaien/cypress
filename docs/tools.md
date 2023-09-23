# Tools

## Introduction

Tools and tool tips

## github cli

Check if installed:

```powershell
winget list --id GitHub.cli
```

If result is "No installed package found matching input criteria.", install by:

```powershell
winget install --id GitHub.cli
```

Check gh auth status:

```powershell
gh auth status
```

Ok status should look something like this:

![gh aut status](2023-01-30-17-03-42.png)

If error message, start interactive [gh auth login](https://cli.github.com/manual/gh_auth_login) by:

```powershell
gh auth login
```

## winget

[winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/) to install and upgrade tools

### add completion to winget

<https://github.com/microsoft/winget-cli/blob/master/doc/Completion.md>

### examples of winget usage

```powershell
winget list --id
winget list --name
winget install --id
winget upgrade --id
winget upgrade
```

## npm

### Optional npm add-on

If you run npm commands very often, install this module globally to make life easier, ref. [organizing npm scripts](https://glebbahmutov.com/blog/organize-npm-scripts/) and [npm-quick-run](https://github.com/bahmutov/npm-quick-run):

```powershell
npm i -g npm-quick-run
```

## mkdocs material

[mkdocs-material](https://squidfunk.github.io/mkdocs-material/)
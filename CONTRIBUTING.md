# Contributing to smb-track
## Commit Messages
Commit messages shall follow the [Angular.js Commit Message Conventions](https://github.com/conventional-changelog/conventional-changelog/blob/a5505865ff3dd710cf757f50530e73ef0ca641da/conventions/angular.md)
</br>
The following is taking directly from the link above:
</br>

### Commit Message Format

Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```
Any line of the commit message cannot be longer 100 characters! This allows the message to be easier to read on github as well as in various git tools.

### Type

Must be one of the following:

* __feat__: A new feature
* __fix__: A bug fix
* __docs__: Documentation only changes
* __style__: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* __refactor__: A code change that neither fixes a bug or adds a feature
* __perf__: A code change that improves performance
* __test__: Adding missing tests
* __chore__: Changes to the build process or auxiliary tools and libraries such as documentation generation

### Scope

The scope could be anything specifying place of the commit change. For example $location, $browser, $compile, $rootScope, ngHref, ngClick, ngView, etc...

### Subject

The subject contains succinct description of the change:

* use the imperative, present tense: "change" not "changed" nor "changes"
* don't capitalize first letter
* no dot (.) at the end

### Body

Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes" The body should include the motivation for the change and contrast this with previous behavior.

### Footer

The footer should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit Closes.

Breaking Changes are detected as such if the footer contains a line starting with BREAKING CHANGE The rest of the commit message is then used for this.

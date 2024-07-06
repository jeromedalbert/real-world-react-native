**NOTE: This project is unmaintained. I am leaving it as an archive.**

# Real World React Native

> Real World React Native apps and their open source codebases for developers to learn from

Learn from React Native apps written by experienced developers.

You'll find the source code for the Real World React Native apps in the [`apps/`](apps/) subdirectory.

Thank you to every developer who has worked on a project this repo links to, your work is helping developers learn React Native.

## How to install on your computer

```bash
# Clone this git repo:
git clone git@github.com:jeromedalbert/real-world-react-native.git

cd real-world-react-native/

# The apps are linked to as git submodules.
# This will take some time...
git submodule update --init
```

## Other Real World codebase collections

- Real World React https://github.com/jeromedalbert/real-world-react
- Real World Ember https://github.com/eliotsykes/real-world-ember
- Real World Rails https://github.com/eliotsykes/real-world-rails
- Real World Sinatra https://github.com/jeromedalbert/real-world-sinatra
- Real World Django https://github.com/ckrybus/real-world-django
- Know any others? Please open a PR and add the link here

## Information for contributors

#### How to add a Real World app

Given a GitHub repo for an app `githubuser/foo`:

```bash
# Inside the project root:
git submodule add -b master git@github.com:githubuser/foo.git apps/foo
```

#### Updating the apps submodules to latest

The apps in `apps/` are git submodules. Git submodules are locked to a revision and don't stay in sync with the latest revision.

To update the revisions, run:

```bash
# This will take some time:
git submodule foreach git pull origin master
```

---

# Contributors

- Jerome Dalbert http://jeromedalbert.com
- Contributions are welcome, fork the GitHub repo, make your changes, then submit your pull request! Reach out if you'd like some help.

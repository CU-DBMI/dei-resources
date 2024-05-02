# Contributing

First of all, thank you so much for contributing! 🎉 💯

This document contains guidelines on how to most effectively contribute within this repository.

If you are stuck, please feel free to ask any questions or ask for help.

## Code of conduct

This project is governed by our code of conduct. By participating, you are expected to uphold this code.
Please report unacceptable behavior to community leader [audrey.hendricks@cuanschutz.edu](mailto:audrey.hendricks@cuanschutz.edu).

## Making changes to this repository

We welcome anyone to use [GitHub issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) (requires a GitHub login), send a [Microsoft Form](https://www.microsoft.com/en-us/microsoft-365/online-surveys-polls-quizzes) entry (for those who may not have a GitHub account) or create [pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (to directly make changes within this repository) to modify content found within this repository.

Specifically, there are several ways to suggest or make changes to this repository:

1. Open a GitHub issue: https://github.com/CU-DBMI/dei-resources/issues (requires GitHub login)
1. Send a Microsoft Form entry: https://forms.office.com/r/RLQNXSSk9V (no login required)
1. Create a pull request from a fork of the repository

### Creating a pull request

### Pull requests

After you’ve decided to contribute code and have written it up, please file a pull request.
We specifically follow a [forked pull request model](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).
Please create a fork of this repository, clone the fork, and then create a new, feature-specific branch.
Once you make the necessary changes on this branch, you should file a pull request to incorporate your changes into this (fork upstream) repository.

The content and description of your pull request are directly related to the speed at which we are able to review, approve, and merge your contribution.
To ensure an efficient review process please perform the following steps:

1. Follow all instructions in the [pull request template](link%20here)
1. Triple check that your pull request is adding _one_ specific feature or additional group of content.
   Small, bite-sized pull requests move so much faster than large pull requests.
1. After submitting your pull request, ensure that your contribution passes all status checks (e.g. passes all tests)

Pull request review and approval is required by at least one project maintainer to merge.
We will do our best to review the code addition in a timely fashion.
Ensuring that you follow all steps above will increase our speed and ability to review.
We will check for accuracy, style, code coverage, and scope.

### Linting

Work added to this repo is automatically checked using [pre-commit](https://pre-commit.com/) via [GitHub Actions](https://docs.github.com/en/actions).
Pre-commit can work alongside your local [git with git-hooks](https://pre-commit.com/index.html#3-install-the-git-hook-scripts)

After [installing pre-commit](https://pre-commit.com/#installation) within your development environment, the following command also can perform the same checks within your local development environment:

```sh
% pre-commit run --all-files
```

We use these same checks within our automated tests which are managed by [GitHub Actions workflows](https://docs.github.com/en/actions/using-workflows).
These automated tests generally must pass in order to merge work into this repository.

# Welcome to the Continuous Coordination contributing guide

Thank you for investing your time in contributing to our project! Any contribution you make will be reflected on [ContinuousCoordination.org](https://ContinuousCoordination.org).

Read our [Code of Conduct](./CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

If git and GitHub aren't familiar to you, please read the "Getting started" section below to familiarize yourself with the types of contributions we're seeking, then contact us at hello@continuouscoordination.org to submit your contribution or notify us of an issue.

## New contributor guide

To get an overview of the project, read the [README](README.md) file. Here are some resources to help you get started with open source contributions in general:

- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)

## Getting started

We'd love to incorporate your contributions in the following areas:

- "Further reading" sections for each principle. Ideally, we'd like to reference lasting, credible materials that are not fleeting artifacts of the current news cycle. See the "citations format" section below for formatting guidelines ([APA style](https://apastyle.apa.org/style-grammar-guidelines/references)).
- Translations from English to other languages, starting with French and Spanish
- Corrections for mistakes, typos, or readability issues
- Edits to "The theory" sections in each principle for clarity or nuance, but sticking with the same tone and style as the rest of the document
- Glossary terms (coming soon)

The original authors and contributors carefully chose the principles, their summaries, and the order in which they appear based on decades of experience in tech and knowledge work. If you submit a contribution that alters the principles themselves, be sure to include a strong argument backed with evidence to support it alongside your submission.

### Citations format for "Further reading"

The "Further reading" items under each principle should adhere to the [APA style guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Use markdown to link the item citation instead of listing the URL separately. Also include a brief description--no more than 2 sentences--of the relevancy to the parent principle. For example:

    - [Clear, J. (2018). _Atomic Habits: An Easy & Proven Way to Build Good Habits & Break Bad Ones_. Avery.](https://www.goodreads.com/book/show/40121378-atomic-habits)
      Decodes the process and positive compounding effect of adopting a series of small habits, like the dual-loop communication approach.

### Issues

#### Create a new issue

If you spot a problem with the docs, [search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments). If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/github/docs/issues/new/choose).

#### Solve an issue

Scan through our [existing issues](https://github.com/github/docs/issues) to find one that interests you. You can narrow down the search using `labels` as filters. See "[Label reference](https://docs.github.com/en/contributing/collaborating-on-github-docs/label-reference)" for more information. As a general rule, we don’t assign issues to anyone. If you find an issue to work on, you are welcome to open a PR with a fix.

### Make Changes

#### Make changes in the UI

Click **Make a contribution** at the bottom of any docs page to make small changes such as a typo, sentence fix, or a broken link. This takes you to the `.md` file where you can make your changes and [create a pull request](#pull-request) for a review.

#### Make changes in a codespace

For more information about using a codespace for working on GitHub documentation, see "[Working in a codespace](https://github.com/github/docs/blob/main/contributing/codespace.md)."

#### Make changes locally

1. Fork the repository.
- Using GitHub Desktop:
  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

- Using the command line:
  - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

2. Create a working branch and start with your changes!

### Commit your update

Commit the changes once you are happy with them. Be sure to use a simple commit message in the present tense (for example, "Add 'alignment trap' to the glossary" instead of "Added an entry to the glossary called alignment trap with a definiton"). Here's a [good guide for this](https://cbea.ms/git-commit/) if you're in doubt. This will help to speed up the review process and keep the commit history tidy.

### Pull Request

When you're finished with the changes, create a pull request, also known as a PR.
- Fill the "Ready for review" template so that we can review your PR. This template helps reviewers understand your changes as well as the purpose of your pull request.
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
Once you submit your PR, a team member will review your proposal. We may ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

### Your PR is merged!

Congratulations, we all appreciate your contribution!

Once your PR is merged, your contributions will be publicly visible on the [Continuous Coordination website](https://continuouscoordination.org).


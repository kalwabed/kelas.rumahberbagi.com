# Contributing to Kelas Rumah Berbagi

- [Contributing to Kelas Rumah Berbagi](#contributing-to-kelas-rumah-berbagi)
  - [How to contribute](#how-to-contribute)
    - [Finding or creating issues](#finding-or-creating-issues)
      - [Open Issues](#open-issues)
      - [Closed Issues](#closed-issues)
      - [For Beginners: `good first issue` label](#for-beginners-good-first-issue-label)
    - [Working on issues](#working-on-issues)
      - [Getting ready](#getting-ready)
      - [Issue assignment & Communication](#issue-assignment--communication)
      - [Creating a Draft Pull Request](#creating-a-draft-pull-request)
      - [Formatting Pull Request Description](#formatting-pull-request-description)
    - [Disabling GitHub Actions](#disabling-github-actions)
  - [FAQ](#faq)
    - [Why are we using English in our issues & PRs?](#why-are-we-using-english-in-our-issues--prs)
  - [Additional Notes](#additional-notes)
    - [Commitlint](#commitlint)
  - [References](#references)
    - [Conventional Commits](#conventional-commits)
      - [Commit types](#commit-types)
      - [Commit scopes](#commit-scopes)
    - [Issue and Pull Request Labels](#issue-and-pull-request-labels)
      - [Type of Issue and Issue State](#type-of-issue-and-issue-state)
      - [Topic Categories](#topic-categories)

## How to contribute

In this project, we are heavily utilising GitHub features to document and signal any progress in the website development.

### Finding or creating issues

Most contributions start from defining issues. Anyone can open an issue for discussion. You can head to [this link](https://guides.github.com/features/issues/) for deep understanding about Issues. Specifically, you can start finding several Issues in [our Issues tab](https://github.com/zainfathoni/kelas.rumahberbagi.com/issues). There are only two categories in Issues section, Open and Closed.

#### Open Issues

Open Issues are issues that need more attention and need to be resolved. Contributors should pick any of the Open Issues and start working on them.

#### Closed Issues

Closed Issues are issues that have been completed or doesn't need further action. Closed issues can be reopened if contributors find any issues related to it sometime in the future.

Please pay attention on every issue attribute. Every issue might be referenced by other contributors through [Linked Pull Requests](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue). If an issue has a linked pull request, that means the issue is currently being handled. To avoid working on the same issue, contributors were strongly encouraged to submit a [draft pull request](https://github.blog/2019-02-14-introducing-draft-pull-requests/) first when they start working on an issue.

#### For Beginners: `good first issue` label

As mentioned [here](https://github.blog/2020-01-22-browse-good-first-issues-to-start-contributing-to-open-source/), `good first issue` is a label feature from GitHub which created to help beginner contributors in contributing to an open-source project. `good first issue` informed us about the difficulty level of an issue. This means that an issue with `good first issue` label suits perfectly for contributors that would like to have their first contribution to an open-source project.

How to find issues with `good first issue` label:

1. The easiest way is to go into the `github.com/<owner>/<repository>/contribute` link. In this case, you can go into [this link](https://github.com/zainfathoni/kelas.rumahberbagi.com/contribute). That link will list all of the issues with the `good first issue` label.
2. Another way is to head over into the [Issues](https://github.com/zainfathoni/kelas.rumahberbagi.com/issues) section of the repository, then click the Labels section beside Milestones. There you can see a lot of labels for the issues in the repository. Then find and click the `good first issue` label.

### Working on issues

#### Getting ready

Before working on an issue, please make sure to:

1. Fork the repo properly. Even you have done it before, it's still advised that you read / skim [the official guide](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository).
2. Clone **your forked repository** and set it up by following the [Getting Started guide](https://github.com/zainfathoni/kelas.rumahberbagi.com#getting-started).
3. Check any open [pull requests](https://github.com/zainfathoni/kelas.rumahberbagi.com/pulls) that no one is working on the issue.
4. Create a new branch from the `main` branch.

#### Issue assignment & Communication

Once you're ready with your branch and have something to contribute, you'll want to
let everyone know that you are working on the issue. To communicate this, we
are using GitHub's Draft Pull Requests.

Draft Pull Request is like a regular Pull Request but it can't be merged until
it's marked as "ready for review". It signals other contributors that [it's a
work in progress](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request).
This is necessary to signal other contributors that the work for the particular
issue has started and it is still in progress. Also, it is a better approach to
use as a communication tool between contributors because we can provide
additional information other than viewing the changed files.

Therefore, when you have at least one commit **it's important to create a Draft
Pull Request** to let everyone know that the issue is assigned to you.

#### Creating a Draft Pull Request

Steps to creating a Draft Pull Request:

1. Commit and push your new changes into the remote repository. Please refer to [@commitlint/config-conventional](https://github.com/conventional-changelog/commitlint/tree/master/@commitlint/config-conventional) for your commit message or you can use [commitlint.io](https://commitlint.io/) to assist you in composing the commit message.
2. Head over to the Pull requests section on your forked repository, hit New pull request.
   ![Hint-1](https://user-images.githubusercontent.com/46013258/126284390-c2bd1aa6-fdc2-4aa6-a945-031f02db038e.png)
3. Pick your forked repository for the head repository, and compare with the branch that you are having changes in.
   ![Hint-2](https://user-images.githubusercontent.com/46013258/126285036-27b49325-62a2-4a6c-b216-5bae261788da.png)
4. Put a clear title and description in your pull request. Make sure the
   description follows [our guide below](#formatting-pull-request-description).
   ![Hint-3](https://user-images.githubusercontent.com/46013258/126286179-04341e30-1224-49cb-9b9a-3c3aee99c308.png)
5. Pick Create draft pull request (like in the image above) and hit the green button.
6. Don't forget to mark your Draft Pull Request as Ready for review after you commit all of the changes.

#### Formatting Pull Request Description

To properly [link a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue), there is one tiny requirement text to put in a Pull Request description.
Please make sure to mention the issue that you're working on correctly. Replace
this text `<!-- mention the issue that you're trying to close with this PR -->`
from the template with the issue number. Example:

```markdown
Closes #318

## Description

Update **`Start working on Issues`** section with clearer instructions on getting ready to work on an issue.
```

### Disabling GitHub Actions

We recommend contributors to disable GitHub action on your forked repository.

1. Go to Setting on your forked repository
2. Choose Action on sidebar
3. Disable Actions
   ![Disable-actions](https://user-images.githubusercontent.com/35433920/129485485-ca7d1202-5dbc-46f7-b823-978d3f4ed600.png)

## FAQ

### Why are we using English in our issues & PRs?

There are several reasons we're using English while communicating in GitHub Issues & PRs:

1. It's more natural for software engineers to communicate in English because it involves many technical terms in English. Trying to translate them into Bahasa Indonesia posing a risk of miscommunication, while keeping them in English requires us to do a lot of _italic_ formatting, according to [PUEBI](https://puebi.js.org/huruf/miring).
2. It accustoms the contributors, which are mostly Indonesian, to communicate in English. It is important to increase our English reading and writing skills because the vast majority of the global open-source communities are using Engish as the main language.
3. It makes this project easier to be recognised globally. So if we need to get more support from the global communities, they could easily understand what we are doing and help us out with their access and competence. e.g., providing us free credits for their services, advocating us to global leaders, or contributing directly to our codebase.

## Additional Notes

### Commitlint

In a repository with many contributors like this, it's important to understand
what's going on in it and navigate between commits. Moreover, with various
levels of contributors & their backgrounds, the commit messages can easily be
confusing and the structure may follow different approaches.

To overcome these issues, the maintainers adopt [commit conventions](https://www.conventionalcommits.org/en/)
to allow contributors to add more semantic meaning to our git history. They use
[commitlint](https://commitlint.js.org/) to lint the git commit messages.
To enforce the conventions, the maintainers use a git hook to run the
commitlint upon a git commit command. This configuration prevents committing the
staged files if the commit message failed to comply with the conventions.

It's adviseable to read the [commit conventions](https://www.conventionalcommits.org/en/v1.0.0)
briefly to further understand the other benefits from them. However, if you're
having problems with it, you can use [this
tool](https://commitlint.io/) to help.

Furthermore, please refer to the list of [commit types](#commit-types) and
[scopes](#commit-scopes) that we use to avoid adding a new scope that has similar
meaning or is synonym to the existing one.

## References

### Conventional Commits

The convention specification looks like this:

```txt
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Commit types

Here are what we use for the commit types:

- `build`
- `chore`
- `docs`
- `feat`
- `fix`
- `perf`
- `refactor`
- `style`
- `test`

#### Commit scopes

Here are what we use for the scopes:

- `assets`
- `ci`
- `cms`
- `components`
  - `donasi`
  - `education`
  - `home`
  - `json-ld`
  - `kontak-darurat`
  - `layout`
  - `telemedicine`
- `cypress`
- `deps`
- `dx`
- `e2e`
- `fetcher`
- `pages`
  - `faq`
  - `isoman`
- `security`
- `seo`
- `ui`

**Note:** If there's a second level in a list, only the lowest level gets to be used.

### Issue and Pull Request Labels

Issue labels are a tool to group issues into one or more categories.
It helps us track and manage issues and pull requests.

Please open an issue on [`zainfathoni/kelas.rumahberbagi.com`](https://github.com/zainfathoni/kelas.rumahberbagi.com/issues) if you have suggestions for new labels.

#### Type of Issue and Issue State

| Label name         | `/kelas.rumahberbagi.com`                                                                   | Description                                                                                                              |
| ------------------ | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `blocked`          | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/blocked)              | Issues blocked by something else.                                                                                        |
| `bug`              | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/bug)                  | Confirmed bugs or reports that are very likely to be bugs.                                                               |
| `enhancement`      | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/enhancement)          | New feature or request.                                                                                                  |
| `epic`             | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/epic)                 | A master issue thread which contains other smaller issues.                                                               |
| `good first issue` | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/good%20first%20issue) | Less complex issues which would be good first issues to work on for users who want to contribute to Kelas Rumah Berbagi. |
| `help wanted`      | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/help%20wanted)        | Issue that need extra attention.                                                                                         |
| `invalid`          | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/invalid)              | Issues which aren't valid (e.g. user errors).                                                                            |
| `question`         | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/question)             | More information needs to be collected about these problems or feature requests (e.g. steps to reproduce).               |
| `wontfix`          | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/wontfix)              | The Kelas Rumah Berbagi team will not fix these issues for now.                                                          |

#### Topic Categories

| Label name      | `/kelas.rumahberbagi.com`                                                            | Description                                   |
| --------------- | ------------------------------------------------------------------------------------ | --------------------------------------------- |
| `ci-cd`         | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/ci-cd)         | Continuous Integration & Continuous Delivery. |
| `design`        | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/design)        | Issue related to design.                      |
| `documentation` | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/documentation) | Improvements or additions to documentation.   |
| `dx`            | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/dx)            | Developer Experience.                         |
| `ui`            | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/ui)            | User interface.                               |
| `ux`            | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/ux)            | User experience.                              |
| `seo`           | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/seo)           | Search engine optimization.                   |
| `scripting`     | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/scripting)     | Issue related to the code.                    |
| `testing`       | [search](https://github.com/zainfathoni/kelas.rumahberbagi.com/labels/testing)       | Automated testing.                            |

# Contributing Guide

Welcome! We are glad that you want to contribute to our project and make it as easy and transparent as possible! If you aren't sure what to expect, here are some guidelines for our project so you feel more comfortable with how things will go.

If this is your first contribution to <project-name>, we encourage you to walk through this guideline helping you to setup your dev environment, make a change, test it and open a pull request about it.

## Code of Conduct
The <project-name> community is governed by our [Code of Conduct](https://github.com/ondat/<project-name>/blob/main/CODE_OF_CONDUCT.md). This includes but isn't limited to: <project-name> GitHub repositories, Discussions, interaction on social media, conferences and meetups.

## License
By contributing, you agree that your contributions will be licensed under its [Apache License 2.0](https://github.com/ondat/<project-name>/blob/main/LICENSE).
In short, when you submit code changes, your submissions are understood to be under the same [Apache License 2.0](https://github.com/ondat/<project-name>/blob/main/LICENSE) that covers the project. Feel free to contact the maintainers if that's a concern.

## Ways to contribute

We welcome many different types of contributions includings:

* Answering questions on [GitHub Discussions](https://github.com/ondat/<project-name>/discussions)
* [Documentation](https://github.com/ondat/<project-name>/wiki)
* Social Media, blog post, webinar
* [Issue triage, new feature, bug fix](https://github.com/ondat/<project-name>/issues)
* Build, CI/CD, QA help, release management
* [Review Pull Request](https://github.com/ondat/<project-name>/pulls)
* Web, logo, diagrams design

Not everything happens through a GitHub pull request. Do not hesitate to start a [GitHub Discussions](https://github.com/ondat/<project-name>/discussions) about any of the above topics or anything other relevant to the project.

## Open an Issue
We are using [GitHub Issues](https://github.com/ondat/<project-name>/issues) to report and track bugs.

When writing a bug report, do it with details, background, and code sample to ease the understanding and help reproducing the
unexpected behavior. Use one of the existing templates or follow some example like [this is one](http://stackoverflow.com/q/12488905/180626) or [another one](http://www.openradar.me/11905408).

**Great Bug Reports** tend to have:

- a quick summary and/or background
- precise steps to reproduce (spending a few extra minutes to document might same hours of ping-pong)
- what you expected would happen
- what actually happens
- any hint towards a possible root cause and fix

***NOTE: do not open a Security related bug or issue. We take security and users' trust seriously. If you believe you have found a security issue in <project-name>, please responsibly disclose by following the [Security Policy](https://github.com/ondat/<project-name>/security/policy).***

## Find an Issue
We use GitHub to host code, track issues and feature requests, as well as accept pull requests. As a start, we have labelled [good first issues](https://github.com/ondat/<project-name>/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) for new contributors and [help wanted](https://github.com/ondat/<project-name>/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) issues suitable for any contributor who isn't a core maintainer.

Sometimes there won't be any issues with these labels. That's ok! There is likely something for you to work on. If you want to contribute but you don't know where to start or can't find a suitable issue, you can reach out via the [GitHub Discussions](https://github.com/ondat/<project-name>/discussions) for guidance.

Once you see an issue that you would like to work on, please post a comment saying that you want to work on it. Something as simple as "I want to work/help on this" is fine :)

## Ask for Help
The best way to reach us with a question when contributing is to ask on [GitHub Discussions](https://github.com/ondat/<project-name>/discussions).

## Which branch to use
For any issues, your branch should be against the ***main*** branch except if explicit guidance within the [GitHub Issues](https://github.com/ondat/<project-name>/issues) description.

## Signing your commits
Licensing is important to open source projects. It provides some assurances that
the software will continue to be available based under the terms that the
author(s) desired. We require that contributors sign off on commits submitted to
our project's repositories. The [Developer Certificate of Origin
(DCO)](https://developercertificate.org/) is a way to certify that you wrote and
have the right to contribute the code you are submitting to the project.

You sign-off by adding the following to your commit messages. Your sign-off must
match the git user and email associated with the commit.

    This is my commit message

    Signed-off-by: Your Name <your.name@example.com>

Git has a `-s` command line option to do this automatically:

    git commit -s -m 'This is my commit message'

If you forgot to do this and have not yet pushed your changes to the remote
repository, you can amend your commit with the sign-off by running

    git commit --amend -s


## When to open a pull request
For none related code changes like like documentation improvement, misspellings and such, you can submit a PR directly including a clear descriptions.

For any code changes, all pull request have to be linked with a [GitHub Issue](https://github.com/ondat/<project-name>/issues). If not, please make an issue first, explain the problem or motivation for the code change you are proposing. When the solution isn't solution is not straightforward, make sure to outline the expected outcome with examples. Your PR will go smoother if the solution is agreed upon via the [GitHub Issue](https://github.com/ondat/<project-name>/issues) before you have spent a lot of time implementing it.

## Pull Request Lifecycle
When you submit your pull request, or you push new commits to it, our GitHub Actions will run some checks on your new code. We require that your pull request passes these checks, but we also have more criteria than just that before we can accept and merge it.

1. You create a draft or WIP pull request. Reviewers will ignore it mostly unless you mention someone and ask for help. Feel
   free to open one and use the pull request to see if the CI passes. Once you are ready for a review, remove the WIP and leave
   a comment that it's ready for review.

   If you create a regular pull request, a reviewer won't wait to review it.

1. A reviewer will assign themselves to the pull request. If you don't see anyone assigned after 3 business days, you can leave
   a comment asking for a review. Sometimes we have busy, sick, vacation days, so a little patience is appreciated ;)

1. The reviewer will leave feedback.
   * Suggestions might be shared that you may decide to incorporate into your pull request or not without further comments.
   * It can help to use a 👍 or a task list/checkbox to track if you have implemented any of the suggestions.
   * It is okay to clarify if you are being told to make a change or if it is a suggestion.

1. After you have made the changes (in new commits please!), leave a comment or check the task list. If 3 business days go by
   with no review, it is ok to bump.

1. If your commits does not content all the suggestions, please open an issue with the title ***Follow-On PR #00***. This will
   allow to pursue or not these suggestions if needed.

1. If your pull request will require a [Documentation](https://github.com/ondat/<project-name>/wiki) update, make sure to provide a
   a extract of what needs to be changed with the proposed changed. Best would be to clone the wiki and perform a parallel pull
   request.

1. When a pull request has been approaved, the reviewer will squash and merge your commits. If you prefer to rebase your own
   commits, at any time leave a comment on the pull request to let them know that.

At this point your changes are available in the ***main*** release of <project-name>! At this stage, the changes are not yet push tagged container image and user will need to build from sources to benefit of your latest and greatest contribution.
The <project-name> maintainers might invite you to be part of the Contributors team - it's up to you to accept ;)

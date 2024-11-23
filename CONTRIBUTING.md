Thank you for investing your time in contributing to our project!

Read our [Code of Conduct](https://github.com/withstudiocms/.github/blob/main/CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

We welcome contributions from the community! Whether it's bug reports, feature requests, or code contributions, we appreciate your help in making this project better.

Table of Contents
- [Bug Reports and Feature Requests](#bug-reports-and-feature-requests)
- [Code Contributions](#code-contributions)
- [Translations](#translations)

# Bug Reports and Feature Requests

If you encounter a bug or want to suggest a new feature, please open an issue on our [GitHub](https://github.com/withstudiocms) on the Repository in question. When creating a new issue, please provide as much detail as possible, including steps to reproduce the issue (for bugs) and a clear description of the proposed feature.

# Code Contributions

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR on the main StudioCMS Monorepo.

If you'd like to contribute code to this project, please follow the steps below:

## Solve an issue

Scan through our [existing issues](https://github.com/withstudiocms/studiocms/issues) to find one that interests you. You can narrow down the search using `labels` as filters. If you find an issue to work on, you are welcome to open a PR with a fix.

## Make Changes

<Steps>
1. Fork the repository.
   - Using GitHub Desktop:
      - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
      - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

   - Using the command line:
      - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

2. Install or update **Node.js** and **pnpm**, to the versions specified in [`.prototools`](https://github.com/withstudiocms/studiocms/blob/main/.prototools). 

3. Create a working branch and start with your changes!

4. Write tests for your changes, if applicable.

5. Update the documentation, if necessary.
</Steps>

## Commit your update

Commit the changes once you are happy with them.

## Pull Request

When you're finished with the changes, create a pull request, also known as a PR.
- Fill the "Ready for review" template so that we can review your PR. This template helps reviewers understand your changes as well as the purpose of your pull request.
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
Once you submit your PR, a Docs team member will review your proposal. We may ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

## Your PR is merged!

Congratulations! The StudioCMS team thanks you. Your contribution will be part of the next release.

Now that you are part of the StudioCMS community, you can help us review other PRs, answer questions, and help other contributors. If you haven't already, join our [Discord](https://chat.studiocms.dev) to connect with other contributors and the StudioCMS team.

# Translations

StudioCMS is a global project, and we want to make it accessible to everyone. If you are fluent in multiple languages, you can help us translate StudioCMS into your language.

## Dashboard i18n

Current translation status:

<img src="https://i18n.studiocms.dev/widget/studiocms/horizontal-auto.svg" alt="Translation status" />

Visit [our i18n dashboard](https://i18n.studiocms.dev) to help translate StudioCMS into your language. If your language is not listed, you can add it within the dashboard.

If you would prefer to contribute translations directly to the repository, the translations are stored in the [`packages/studiocms_core/src/i18n/translations`](https://github.com/withstudiocms/studiocms/tree/main/packages/studiocms_core/src/i18n/translations/) directory. You can find the English translations in the [`en-us.json`](https://github.com/withstudiocms/studiocms/blob/main/packages/studiocms_core/src/i18n/translations/en-us.json) file.

<ReadMore>
StudioCMS uses [Weblate](https://weblate.org) for managing translations on top of GitHub. If you are new to Weblate, you can find the [Translating using Weblate Guide](https://docs.weblate.org/en/latest/user/translating.html#) on their website.
</ReadMore>

Once the translations have been added, they will be added to the [StudioCMS i18n configuration](https://github.com/withstudiocms/studiocms/blob/main/packages/studiocms_core/src/i18n/index.ts#L8) and will be available in the next release.

## Documentation

**Coming soon!** We are working on prepping to translate the StudioCMS documentation. If you are interested in helping with this, please reach out to us on [Discord](https://chat.studiocms.dev)

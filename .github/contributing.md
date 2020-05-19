# Contributing to Everest Forms Developer Documentation ✨

There are many ways to contribute to the Everest Forms development documentation!

- Sending PR for translation, or missing resources on the knowledgebase.
- Answering questions on GitHub and within the various Everest Forms communities.
- Submitting fixes, improvements, and enhancements.

Your help making Everest Forms even more awesome will be greatly appreciated :)

If you think something can be improved and you wish to contribute code,
[fork](https://help.github.com/articles/fork-a-repo/) Everest Forms, commit your changes,
and [send a pull request](https://help.github.com/articles/using-pull-requests/). We'll be happy to review your changes!

## Feature Requests

Feature requests can be [submitted to our issue tracker](https://github.com/wpeverest/everest-forms/issues/new?template=Feature_request.md). Be sure to include a description of the expected behavior and use case, and before submitting a request, please search for similar ones in the closed issues.

Feature request issues will remain closed until we see sufficient interest via comments and [👍 reactions](https://help.github.com/articles/about-discussions-in-issues-and-pull-requests/) from the community.

You can see a [list of current feature requests which require votes here](https://github.com/wpeverest/everest-forms/issues?q=label%3A%22votes+needed%22+label%3Aenhancement+sort%3Areactions-%2B1-desc+is%3Aclosed).

## Technical Support / Questions

We don't offer technical support on GitHub so we recommend using the following:

**Reading our documentation**
Usage docs can be found here: https://docs.wpeverest.com/docs/everest-forms/

If you have a problem, you may want to start with the self help guide here: https://docs.wpeverest.com/docs/everest-forms/self-service-guide/

**Technical support for premium addons or if you're a WPEverest.com customer**
 from a human being - submit a ticket via the helpdesk
https://wpeverest.com/contact/

**General usage and development questions**
- WordPress.org Forums: https://wordpress.org/support/plugin/everest-forms

## Code of conduct

Everest Forms has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](.github/CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## Coding Guidelines

- **Ensure you stick to the [WordPress Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/)**
- Install our pre-commit hook using composer. It'll help with the Coding Standards. To install run `composer install` from the command line within the everest-forms plugin directory.
- Ensure you use LF line endings in your code editor. Use [EditorConfig](http://editorconfig.org/) if your editor supports it so that indentation, line endings and other settings are auto configured.
- When committing, reference your issue number (#1234) and include a note about the fix.
- Ensure that your code is compatible with PHP 5.4+.
- Push the changes to your fork and submit a pull request on the master branch of the Everest Forms repository. Existing maintenance branches will be maintained by Everest Forms developers.

Please **don't** modify the changelog or update the .pot files. These will be maintained by the Everest Forms team.

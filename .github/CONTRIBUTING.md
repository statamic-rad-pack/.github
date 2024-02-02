# Contributing
✨ Before we get started, thank you for taking the time to contribute! ✨

This is the Contributing Guide for all addons in the [Statamic Rad Pack](https://github.com/statamic-rad-pack). We welcome your feedback, proposed changes, and updates to these guidelines. We will always welcome thoughtful issues and consider pull requests.

## What You Should Know Before Contributing

### How to Get Support
All of the addons in the Rad Pack are maintained by contributors in their free time. As such, there's no special "support system" for issues you're running into.

If you need help, you can ask the community via GitHub Discussions or on the [`#rad-pack-support`](https://discord.gg/ytqCaQUxTv) channel on Discord.

## How You Can Contribute

### Bug Reports
First things first. If the bug is security related refer to our [security disclosures](./SECURITY.md) procedures instead of opening an issue.

Next, please search through the open issues to see if it has already been opened.

If you do find a similar issue, upvote it by adding a 👍 reaction. Only leave a comment if you have relevant information to add.

If no one has filed the issue yet, feel free to submit a new one. Please include a clear description of the issue, follow along with the issue template, and provide and as much relevant information as possible. Code examples demonstrating the issue are the best way to ensure a timely solution to the issue.

### Feature Requests
If you have a feature request, please open a GitHub Discussion in the relevant category.

### Security Disclosures
If you discover a security vulnerability, please review our [Security Policy](./SECURITY.md), then report the issue directly to the Statamic Core Team from [statamic.com/support](https://statamic.com/support). We will review and respond privately via email.

### Documentation Edits
Usually, you'll find the documentation for an addon inside the `docs` directory, inside a `DOCUMENTATION.md` file or the addon's `README.md`.

You can submit improvements or corrections to them via a pull request.

### Compiled Assets
If you are submitting a change that will affect a compiled file, such as most of the files in `resources/css` or `resources/js`, **do not** commit the compiled files.

Due to their large size, they cannot realistically be reviewed by maintainers. This could be exploited as a way to inject malicious code into Statamic. In order to defensively prevent this, all compiled files will be generated upon release by GitHub Actions.

### Pull Requests
Pull requests should clearly describe the problem and solution. Include the relevant issue number if there is one. If the pull request fixes a bug, it should include a new test case that demonstrates the issue, if possible.

Creating a pull request that introduces a new feature or changes current behavior? Please include updates to any relevant documentation in your PR.

PR titles should include the major version number they're targeted at — e.g. [4.x] or [3.x].

<br>
Thank you! Stay rad. If you're not already rad, tell us and we will make it so.

:sparkles:

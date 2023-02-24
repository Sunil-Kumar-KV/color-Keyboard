# Contributing to Keyboard CSS

🙏 I would ❤️ for you to contribute to Keyboard CSS and help make it even better than it is today!

## Developing

Start by cloning the project and installing all dependencies:

```bash
git clone https://github.com/shhdharmen/keyboard-css.git
cd keyboard-css
npm i
```

Run the playground app:

```bash
npm start
```
## Building

Building and publishing is done through semantic-release and github actions.

As the [@semantic-release/npm](https://github.com/semantic-release/npm) plugin uses the npm CLI to update the package.json version and publish the package, all npm hook scripts will be executed.

We are using the `postversion` hook so it will be executed during the prepare step of [@semantic-release/npm](https://github.com/semantic-release/npm), which allow for example to update files before committing them with the [@semantic-release/git](https://github.com/semantic-release/git) plugin.

More at: [How can I use a npm build script that requires the `package.json`'s version ?](https://semantic-release.gitbook.io/semantic-release/support/faq#how-can-i-use-a-npm-build-script-that-requires-the-package-jsons-version).

<!-- markdownlint-disable -->
## <a name="rules"></a> Coding Rules
<!-- markdownlint-restore -->

To ensure consistency throughout the source code, keep these rules in mind as you are working:

- All features or bug fixes **must be tested** by one or more specs (unit-tests).
- All public API methods **must be documented**.

<!-- markdownlint-disable -->
## <a name="commit"></a> Commit Message Guidelines

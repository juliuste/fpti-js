# contributing guidelines

Thanks for bringing your ideas into this project!

- Because this project tries is community-lead, **you should propose all changes as [issues](https://help.github.com/articles/about-issues/) or [pull requests](https://help.github.com/articles/about-pull-requests/).** Thus, everyone can then voice their opinion on the change and it can be adapted.
- To propose large or potentially controversial changes, open an issue first. We can then discuss wether it's worth investing time into a pull request. Submit small changes such as corrected typos as pull requests immediately.
- By participating in this project, you commit to the [code of conduct](code-of-conduct.md).

## adapting the spec

- Make sure that you update all files that implicitly depend on the spec, such as examples or the readme.

## creating a new version

- This project follows [SemVer](http://semver.org). **Increase the *major* version number whenever the new version might break dependent projects.**
- **[Tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging) the commit** with the new version, e.g. by running `git tag -a 0.7.1 -m 'v0.7.1'`. This is important for dependant projects to be able to reference a specific version of the spec.

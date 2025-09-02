# CONTRIBUTING

Contributions are always welcome, no matter how large or small. Before contributing,
please read the [code of conduct](CODE_OF_CONDUCT.md).

Some thoughts to help you contribute to this project

## Recommended Communication Style

1. Always leave screenshots for visuals changes
1. Always leave a detailed description in the Pull Request. Leave nothing ambiguous for the reviewer.
1. Always review your code first. Do this by leaving comments in your coding noting questions, or interesting things for the reviewer.
1. Always communicate. Whether it is in the issue or the pull request, keeping the lines of communication helps everyone around you.

## Setup (forks are preferred).

```sh
$ git clone https://github.com/<your-name>/pycontg25
$ cd pycontg25
$ python3.11 -m venv pytg # to create virtual env
$ source pytg/bin/activate # for linux users
$ source pytg/Scripts/activate # for windosw users
$ pip install -r requirements.txt
```

## Building

```sh
$ python app.py
```

## Testing
For running the test suite, use the following command.
```sh
$ python -m unittest
```

## Pull Requests

### _We actively welcome your pull requests, however linking your work to an existing issue is preferred._

1. Fork the repo and create your branch from `beta` or DEFAULT branch if different.
1. Name your branch something that is descriptive to the work you are doing. i.e. adds-new-thing or fixes-mobile
1. If you've added code that should be tested, add tests.
1. If you've changed APIs, update the documentation.
1. If you make visual changes, screenshots are required.
1. Ensure the test suite passes.
1. Make sure you address any lint warnings.
1. If you make the existing code better, please let us know in your PR description.
1. A PR description and title are required. The title is required to begin with: "feat:" or "fix:"
1. [Link to an issue](https://help.github.com/en/github/writing-on-github/autolinked-references-and-urls) in the project. Unsolicited code is welcomed, but an issue is required for announce your intentions. PR's without a linked issue will be marked invalid and closed.

### PR Validation
Examples for valid PR titles:

- fix: Correct typo.
- feat: Add support for Python 3.13.
- doc: Update README with new example.
- refactor!: Drop support for Python 3.6.

_Note that since PR titles only have a single line, you have to use the ! syntax for breaking changes._

See [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for more examples.

### Work in progress
GitHub has support for draft pull requests, which will disable the merge button until the PR is marked as ready for merge.

## Issues
If you plan to contribute a change based on an open issue, please assign yourself by commenting on the following word `.take`. Issues that are not assigned are assumed open, and to avoid conflicts, please assign yourself before beginning work on any issues.

Also, all questions are welcomed.

## Funding
Python Togo is not yet part of GitHub Sponsors. If you would like to contribute, please note the founder's [sponsor page](https://github.com/sponsors/wasscodeur); for details on how funds are distributed, check our upcoming gitbook annual report.

## Community
Do you have questions? Join the conversation in our [Discord](https://pytogo.org/discord).

## License

By contributing to the Python Togo project, you agree that your contributions will be licensed
under its [Apache 2.0 license](LICENSE).

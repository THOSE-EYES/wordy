# Contributing to the Wordy

The following is a summary of the process for contributing changes to the Wordy. For detailed information, please refer to the [Wordy Development Guide](https://google.github.io/styleguide/cppguide.html).

## Patches

The Wordy uses GitHub for development and code review. To contribute patches:

1. Fork the upstream [Wordy Repository](https://github.com/THOSE-EYES/wordy) into your personal GitHub account.
2. Follow the [Source Code Guidelines](https://google.github.io/styleguide/cppguide.html) for coding standards.
3. Create a topic branch with a descriptive name for your work. Start from the `main` branch for new work. Use the `release` branch only for fixes targeting specific releases.
   - If uncertain, default to `main`. Reviewers might request a rebase if needed.
4. Make commits with clear, incremental, and logically complete changes, using the [.gitmessage](.gitmessage) file.
5. Push your topic branch to your personal repository fork on GitLab.
6. Create a Merge Request targeting the `main` branch (even for changes intended for `release`). Enable the option to "Allow commits from members who can merge to the target branch" so maintainers can make minor edits if necessary.

## License

We do not require any formal copyright assignment or contributor license agreement. Contributions submitted to the Wordy are assumed to be offered under the MIT License. See [LICENSE.md](LICENSE.md) for details.


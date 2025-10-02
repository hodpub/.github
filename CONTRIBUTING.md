# Hod Publishing - Contributing to our projects!

First off, thank you for considering contributing to any of our systems/projects.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing these open source projects. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

## 🤖 AI Usage

As we work with several publishers, we ask you to refrain any usage of AI while contributing to our projects. Foundry has a policy to tag any module/system that used AI, and Foundry community is not favour of this kind of usage. Given that, if you use any kind of AI, we have to say thanks, but we will not be able to take in your contribution on the project.

### Table of contents

1. [Commit Messages](#pencil-commit-messages)

2. [Localization](#globe_with_meridians-localization)

3. [How do I Contribute?](#hammer_and_wrench-how-do-i-contribute)

4. [Pull Requests](#dart-pull-requests)

5. [Community](#people_holding_hands-community)

## :pencil: Commit Messages

We use a variation of the [Conventional Commits Standards](https://www.conventionalcommits.org/en/v1.0.0/), called [GitMoji](https://gitmoji.dev/). You can find below the emojis we use for the types:

- ✨ Feature work
- 🐛 Bug Fix
- 🌐 Translations
- 📝 Documentation

Please, use the follwing pattern to your commits:

```
<emoji> (<issue>): Description
# Examples
✨ (#1) Implement weapon roll with bonus
🐛 (#2) Fix attack damage
🌐 Update German language
📝 Include weapon roll explanation
```

Please, use the issue number whenever is possible.

## :globe_with_meridians: Localization

We are grateful for any and all localization support we can get. Language files can be found in the `/lang`-directory. The files are named according to the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) standard.

See [How do I contribute?](#hammer_and_wrench-how-do-i-contribute) for more information.

## 🛠️ How do I contribute?

> Glad you asked!

### Open issues

At any time the project has [a few open issues](/../../issues). If there is anything in there you think you would want to cut your teeth on, please do! Check [open pull requests](/../../pulls) first to see if there are anyone working on the issue. If you decide to tackle an issue, assign yourself to it, or comment on it, to indicate that you intend to work on it.

### Raise an issue

Maybe you have found a bug, or maybe you have a feature in mind that you would like to see implemented. Head over to the [issue tracker](/../../issues) first, and see if it is already listed there. If it is not, go ahead and open an issue, if it is feel free to bump it or comment on it.

If you want to work on a bug or a feature yourself, please raise an issue first then assign yourself to it or indicate that you will be working on it. This way we don't end up with two people working on the same thing:bulb:

### Localization

We are grateful for any and all localization support we can get. Language files can be found in the `/lang`-directory. The files are named according to the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) standard. If you want to contribute with localization, please follow these steps:

1.  Fork the repository.
2.  Create a new branch from the `main` branch (a GUI app may help with the git operations. E.g. [Github Desktop](https://desktop.github.com/)).
3.  Make your changes in the `.json`-file for your desired language, or make a new one\*. You can reference the `en.json`-file to see what keys are used.
4.  Commit your changes. Make sure to follow the pattern explained at [Commit Messages](#pencil-commit-messages).
5.  Push your changes to your fork.
6.  Open a pull request to the `main` branch of the repository.

\*If you are making a new file, make sure to add it to the `/system.json`-file.

### Spread the word

We are always looking for someone who can help with the project or one of the other projects in our organization. If you do not feel like you can contribute yourself, maybe you know someone who can:vulcan_salute:

## :dart: Pull Requests

When you are ready to submit a pull request, make sure you do a few things to help speed up the process.

1.  Keep it tidy. Fewer commits with changes logically grouped together makes it easier to review them.
2.  Now you are ready to submit a Pull Request. The project's `trunk` is a branch called `main`. When submitting a Pull Request make sure to point it to the `main` branch.
3.  When creating the Pull Request, consider prefacing the title with [an emoji that indicates the type of pull request](https://gitmoji.dev/).
4.  Briefly describe the pull request and whether you have made any deletions or modifications that may be breaking.
5.  That's it! Thank you so much for your help with improving this project:purple_heart:

### Code review process

The team is always open to discuss the ideas. Keep in mind that sometimes we will not be able to share full context of some systems/issues because of some possible NDAs.
All feedback will follow our code of conduct and has the intention to improve the code, keeping the current quality or improving it.

## :people_holding_hands: Community

You can chat with the team on https://hodpub.com/discord, on Foundry Discord server and on the Year Zero Worlds Discord server.

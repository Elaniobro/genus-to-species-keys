[![All Contributors](https://img.shields.io/github/all-contributors/elaniobro/genus-to-species-keys?color=ee8449&style=flat-square)](#contributors)

# genus-to-species-keys
typeahead search for keys to species
## Table of Contents

- [API Key & Documentation](#-api-key--documentation)
- [Best Practice](#-best-practice)
- [Build Setup](#-build-setup)
- [Code Commits](#-code-commits)
- [Contributor(s)](#-contributors)
- [How to use this application](#ℹ️-how-to-use-this-application)

## ℹ️ How to use this application

1. clone this repo with the following command: `git clone https://github.com/Elaniobro/genus-to-species-keys.git`
1. install all the node modules with `pnpm install`


## 🚧 Build Setup

```bash
# install dependencies
$ pnpm install
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## 🔑 API Key & Documentation:
TBD...


### 💻 Code Commits

This application uses pre-commit checks and pre-push validation. This repo also follow [commitizen](https://commitizen-tools.github.io/commitizen/) and [commitlint](https://github.com/conventional-changelog/commitlint) standards
To use the interactive commit tool, after you install the node modules you _should now_ be able to simply put: `cz` to create your commit message using the interactive menu.

### 👚 Linting

This repo also has specific guidlines built into it, to help reduce the strain on code reviews. These rules are subject to change, but should ONLY be ammended through a pull request pending a code review. The files are also ran through a linter on `staged files` to verify that they adhere to the rules. You may run the command at anytime locally to check yourself.

```bash
pnpm lint:js       # checks */**[.js,.ts,.vue]
pnpm lint:prettier # checks .
pnpm lint:style    # checks */**[.vue,.css,.scss]
```

You may also check all 3 at once:

```bash
pnpm lint          # runs eslint, prettier and stylelint
```

If any of the linters returns an error, you may try to autofix running the following:

```bash
pnpm lint:fix
```

## 🧪 Testing

TBD

## ⭐ Best Practice

Please prefix all git branches with `



` for `Genus to Species Keys` and be succint in the branch description:

```bash
$ git branch
* main
$ git checkout -b mybranch-name
Switched to a new branch 'mybranch-name'
$ git branch
* mybranch-name
  main
```

use the imperative voice and try to keep the title commit under 50 characters. This can be done when saying to yourself, "this commit will: `your commit message here`."
_replace the code block in the quote with the commit message_

```bash
git commit -m "docs(readme):  add more sections"
```


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/elaniobro"><img src="https://avatars.githubusercontent.com/u/710847?s=100" width="100px;" alt=""/><br /><sub><b>Elaniobro</b></sub></a><br /><a href="https://github.com/Elaniobro/genus-to-species-keys?author=elaniobro" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

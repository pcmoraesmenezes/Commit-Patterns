# Commit Patterns 📝

Commit Patterns is a tool to help you write better commit messages. It is a command line tool that will check your commit messages against a set of rules and warn you if they do not pass.

Is useful to improve clearness and readability of your commit messages.

According to [Convetional Commits](https://www.conventionalcommits.org/en/v1.0.0/), it provides an easy set of rules for creating an explicit commit history; which makes it easier to write automated tools on top of.

## Types and Descriptions 📌

| Type     | Description                                                                 |
| -------- | --------------------------------------------------------------------------- |
| feat     | A new feature (MINOR in semantic version) |
| fix      | A bug fix (PATCH in semantic version) |
| breaking change or ! |  Introduces a breaking API change (Correlating with MAJOR) in Semantic Versioning. May be provided and follow a convention similiar to commit patterns |
| docs     | Documentation Changes (Do not incude changes in code) |
| style    | Change in code formatting. (Do not include changes in code) |
| refactor | Change in code that neither fixes a bug nor adds a feature, but have some performance improvement |
| perf     | Change in code that improves performance |
| test     | Adding missing tests or correcting existing tests (Do not include changes in code) |
| build    | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm) |
| ci       | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) - CI means Continuous Integration |
| chore    | Changes in tasks that are not related to src or test files. Such as updating build tasks, package manager, gitignore. (Do not include changes in code) |
| revert   | Revert to a commit |
| wip      | Work in progress (Do not include changes in code) |
| raw | Changes releated to config files, datas, features, etc. |

---

### Recomentations and add-ons to commit messages ✏️

- Baseboard: Information about the reviewer, like: Reviewed-by: @user

- Body: Descriptions about the commit, showing the reason for the change, the context and the differences between the previous and the current version. Exemple: See the issue on the top of the file.

- Description: Descriptions about commit. Example: Adding some tests to the project.

#### Use emojis to make your commit messages more readable and fun 💈


| Emoji | Raw Emoji Code | Description |
| :---: | :------------: | ----------- |
| 🎉 | `:tada:` | Initial commit |
| 🎨 | `:art:` | Improving structure / format of the code |
| 🏇 | `:racehorse:` | Improving performance |
| 📝 | `:memo:` | Writing docs |
| 🐛 | `:bug:` | Fixing a bug |
| 🔥 | `:fire:` | Removing code or files |
| 🔒 | `:lock:` | Fixing security issues |
| 💩 | `:poop:` | Writing bad code that needs to be improved |
| 🚧 | `:construction:` | Work in progress |
| ✨ | `:sparkles:` | Introducing new features |
| 🚀 | `:rocket:` | Deploying stuff |
| 🙈 | `:see_no_evil:` | Adding or updating a .gitignore file |
| 🧪 | `:alembic:` | Experimenting new things |
| ☸️ | `:wheel_of_dharma:` | Changing configuration files |
| ♻️ | `:recycle:` | Refactoring code |
| ✅ | `:white_check_mark:` | Adding or updating tests |
| 💚 | `:green_heart:` | Fixing CI Build |
| 🔒 | `:lock:` | Fixing security issues |
| 🔼 | `:arrow_up:` | Upgrading dependencies |
| 🔽 | `:arrow_down:` | Downgrading dependencies |
| 👕 | `:shirt:` | Removing linter warnings |
| 📈 | `:chart_with_upwards_trend:` | Adding or updating analytics or track code |
| 🔨 | `:hammer:` | Work in progress |
| ➕ | `:heavy_plus_sign:` | Adding a dependency |
| ➖ | `:heavy_minus_sign:` | Removing a dependency |
| 🔊 | `:speaker:` | Adding logs |
| 🔇 | `:mute:` | Removing logs |
| 🌐 | `:globe_with_meridians:` | Internationalization and localization |
| 🔧 | `:wrench:` | Changing configuration files |
| ✏️ | `:pencil2:` | Fixing typos |
| 💩 | `:hankey:` | Writing bad code that needs to be improved |
| 🔀 | `:twisted_rightwards_arrows:` | Merging branches |
| 📦 | `:package:` | Updating compiled files or packages |
| 👽 | `:alien:` | Updating code due to external API changes |
| 🚚 | `:truck:` | Moving or renaming files |
| 📄 | `:page_facing_up:` | Adding or updating license |
| 💥 | `:boom:` | Introducing breaking changes |
| 🍱 | `:bento:` | Adding or updating assets |
| 👌 | `:ok_hand:` | Updating code due to code review changes |
| ♿ | `:wheelchair:` | Improving accessibility |
| 💡 | `:bulb:` | Documenting source code |
| 🍻 | `:beers:` | Writing code drunkenly |
| 📚 | `:books:` | Writing docs |
| ✏️ | `:pencil:` | Writing code |
| 👷‍♂️ | `:construction_worker:` | Adding CI build system |
| 🧪 | `:alembic:` | Experimenting new things |
| 🔍 | `:mag:` | Improving SEO |
| 🏷️ | `:label:` | Adding or updating types (Flow, TypeScript) |

---

## Examples

| Git command | Result in Github |
| ----------- | ---------------- |
| git commit -m ":tada: init: Initial commit" | 🎉 init: Initial commit |
| git commit -m ":bug: fix: Fixing a bug" | 🐛 fix: Fixing a bug |
| git commit -m ":sparkles: feat: Introducing new features" | ✨ feat:  Introducing new features |
| git commit -m ":memo: docs: Writing docs" | 📝 docs: Writing docs |
| git commit -m ":art: style: Improving structure / format of the code" | 🎨 style: Improving structure / format of the code |
| git commit -m ":racehorse: perf: Improving performance" | 🏇 perf: Improving performance |
| git commit -m ":test_tube: test: Adding or updating tests" | 🧪 test: Adding or updating tests |
| git commit -m ":recycle: refactor: Refactoring code" | ♻️ refactor: Refactoring code |
| git commit -m ":rocket: chore: Deploying stuff" | 🚀 chore: Deploying stuff |
| git commit -m ":construction: wip: Work in progress" | 🚧 wip: Work in progress |
| git commit -m ":poop: chore: Writing bad code that needs to be improved" | 💩 chore: Writing bad code that needs to be improved |
| git commit -m ":lock: chore: Fixing security issues" | 🔒 chore: Fixing security issues |
| git commit -m ":bulb: chore: Documenting source code" | 💡 chore: Documenting source code |
| git commit -m ":twisted_rightwards_arrows: chore: Merging branches" | 🔀 chore: Merging branches |


---
 

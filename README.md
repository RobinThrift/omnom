# omnom
[![travis](https://img.shields.io/travis/RobinThrift/omnom.svg?style=flat-square)](https://travis-ci.org/RobinThrift/omnom)
![deps](https://img.shields.io/david/RobinThrift/omnom.svg?style=flat-square)
![travis](https://img.shields.io/david/dev/RobinThrift/omnom.svg?style=flat-square)

## Installation
`$ npm install -g omnom`

## Usage
- `$ omnom <GENERATOR> [OPTIONS]`
- `$ omnom help` for more info

## Included Generators
- `wiktionary`: `omnom wiktionary [OPTIONS] <FORMAT>`
    - `FORMAT`: Can be any number of Alphanumeric characters plus `_.-`. [:name] will be understood as the word category "name" and will be resolved with wiktionary.
    - `-n, --count`: Will produce n code names

## Git Commit Messages

- Use the past tense ("Added feature" not "Add feature")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally
- Consider starting the commit message with an applicable emoji:
 - ➕ when adding a feature
 - ➖ when removing a feature
 - 🎉 when improving a feature
 - 🎨 when improving the format/structure of the code
 - 🐎 when improving performance
 - 🚱 when plugging memory leaks
 - 🔞 when using dirty hacks
 - 📝 when writing docs
 - 🐛 when fixing a bug
 - 🔥 when removing code or files
 - 💚 when fixing the CI build
 - 💻 when making changes to the infrastructure
 - ✅ when adding tests
 - 🔒 when dealing with security
 - ⬆️ when upgrading dependencies
 - ⬇️ when downgrading dependencies
 - 👕 when removing linter warnings

([source](https://atom.io/docs/latest/contributing#git-commit-messages))

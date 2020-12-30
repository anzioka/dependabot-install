# dependabot-install
Simple python script that wraps around GitHub CLI (https://cli.github.com/) to automate installing node dependencies and dev dependencies. Fetches pull requests opened by Dependabot and upgrades packages to the listed versions

## Requirements
- colorama(https://pypi.org/project/colorama/) `pip install colorama`
- GitHub CLI (https://cli.github.com/) `brew install gh`

## Usage
`python main.py <dir>` where `dir` is the root directory of repository to fetch dependencies from


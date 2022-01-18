# List commits extension
It is a gh extension for listing all of the commits in a PR.

## Installation
```bash
gh extension install devanshutanna/gh-list-commits
```

## Usage
```bash
gh list-commits (-P|--pull)={pull_number} (-R|--repo)={repo_name} (-O|--owner)={owner_username}
```
**Example**
```bash
gh list-commits -P=100
```


### Options
* `-P`, `--pull <number>
    **Required** The pull request number in Github

* `-O`, `--owner <string>`
    The username of the repository owner

* `-R`, `--repo <string>`
    The name of the repository

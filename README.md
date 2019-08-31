# workflows

Github Workflows as a SubTree

## Example

1. Assume a repository does not have the `.github/workflow` folder yet.
1. Go to the local repository folder. Let's say this folder is `.`.
1. Prepare a `pytest` setup under `./tests/` folder.
1. `mkdir ./.github`
1. Add this repository as a subtree of the repository.
    `git subtree add --prefix=./.github/workflows/ https://github.com/kangwonlee/workflow.git master --squash`
1. Make changes to files of `./.github/workflows/` as necessafy & commit.
1. Push to GitHub.

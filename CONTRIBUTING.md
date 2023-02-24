# Contributing

Contributions are welcomed assuming my repositories are the correct place
for it (the target is my repository or a PR I have open to another repository).

Issues being assigned to me doesn't matter, I use that just as a tool for
rediscovering them easily, http://github.com/issues?q=is:open%20assignee:Mikaela

I also accept PRs to repositories that are mirrors (if that is easier for you
than opening at the original location) as patches are easy enough to export
from GitHub or `git remote`s to use, the merge might just take a bit longer
(including the time the mirror takes to update).

## General steps

1. In case [editorconfig](https://editorconfig.org/) isn't
   [natively supported by your editor of choice](https://editorconfig.org/#pre-installed),
   please consider [installing a plugin](https://editorconfig.org/#download).  
   E.g. VS Cod{e,ium} users can `CTRL-P` and execute `ext install EditorConfig.EditorConfig`.
2. If the repository in question has a `.pre-commit-config.yaml` file,
   please install [`pre-commit`](https://pre-commit.com/) and run
   `pre-commit install` in your local clone at least once.

-  [![Packaging status of pre-commit](https://repology.org/badge/vertical-allrepos/python:pre-commit.svg)](https://repology.org/project/python:pre-commit/versions)

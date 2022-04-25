# bwa-meme_bwakit

## Tools and intent

Thie repo has been created to build a container with tools to support a mapping flow using pipes for efficient I/O:

- samtools
- bwa-meme
- bwakit (direct use of scripts, not wrapper)

## pre-commit

The report has a base pre-commit configuration to aid in standards for the repository and ensuring secrets are not accidentally
imported.  Please see thr [pre-commit] docs for how to activate this in your workspace.

## Versioning

Please use semver, this is essential to ensure the docker images build and push as expected via Actions:

https://github.com/docker/metadata-action#semver

## Removing the repo

If the repository was created as an interim solution or for testing purposes please ensure that the quay.io repository
is removed at the same time to reduce noise in our organisations.

<!-- refs -->

[pre-commit]: https://pre-commit.com/

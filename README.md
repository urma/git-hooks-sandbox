# git hook template project

## Introduction
This repository contains sample hook scripts which should be used as a
template for any new repositories created. These will enforce client-side
checks to prevent secrets and insecure code from being committed.

## Usage
When creating a new repository, simply use the `--template` parameter to point
to the `git-template` directory of this repository:

```
$ mkdir new-repository
$ cd new-repository
$ git init --template=/path/to/repository-template/git-template
```

## Prerequisites
* `git-secrets`
* `trufflehog`

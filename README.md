# TRLN Developer Documentation

General documentation for development practices and workflows

## General Principles

### Multiple sets of eyes on all changes

Use pull requests for all changes.  Pull requests cannot be merged by their creators.

# Git Workflow for All Projects

(somewhere in between GitHub flow and Git Flow)

`master` is for production-ready code (working, deployable)

`develop` is for current development; when `develop` is deemed to be production ready (release-worthy), it is merged to `master`

## Branching

All development should start in a local branch following these naming conventions:

`issue-{issue number}` for code that addresses a named issue -- for this reason, you should probably create an issue before you start work.


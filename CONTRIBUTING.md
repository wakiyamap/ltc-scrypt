# Contributing guide

This software is open source software, and contributions which improve the
state of the software are welcome.

## Branches and tags

The default integration branch is `main`, which serves as the base for all
generic pull requests.

NOTE: A `master` branch exists, but only serves archive purposes as some
      versions of Dogecoin Core's QA scripts hard link against that branch.

Whenever the software is ready for release, maintainers will update the version
and tag the commit that finalizes that version. Due to the simplicity of this
software, maintenance branches are currently not foreseen, but may be introduced
in the future.

## Contributor Workflow

The codebase is maintained using the "contributor workflow" where everyone
without exception contributes patch proposals using "pull requests". This
facilitates social contribution, easy testing and peer review.

To contribute a patch, the workflow is as follows:

  - Fork the repository in GitHub, and clone it your development machine.
  - Create a topic branch from the relevant development branch.
  - Commit changes to the branch.
  - Push the topic branch to your copy of the repository.
  - Raise a Pull Request via GitHub.

In general [commits should be atomic](https://en.wikipedia.org/wiki/Atomic_commit#Atomic_commit_convention)
and diffs should be easy to read. For this reason do not mix any formatting
fixes or code moves with actual code changes.

Commit messages should be verbose by default consisting of a short subject line
(50 chars max), a blank line and detailed explanatory text as separate
paragraph(s); unless the title alone is self-explanatory (like "Corrected typo
in init.cpp") then a single title line is sufficient. Commit messages should be
helpful to people reading your code in the future, so explain the reasoning for
your decisions. Further explanation [here](http://chris.beams.io/posts/git-commit/).

Please refer to the [Git manual](https://git-scm.com/doc) for more information
about Git.

The body of the pull request should contain enough description about what the
patch does together with any justification/reasoning. You should include
references to any discussions (for example other tickets or mailing list
discussions). At this stage one should expect comments and review from other
contributors. You can add more commits to your pull request by committing them
locally and pushing to your fork until you have satisfied feedback.

## "Decision Making" Process

Whether a pull request is merged rests with the repository maintainers.

Maintainers will take into consideration if a patch is in line with the general
principles of the software; meets the minimum standards for inclusion; and will
take into account the consensus among frequent contributors.

In general, all pull requests must:

  - have a clear use case or fix a demonstrable bug
  - be peer reviewed
  - where bugs are fixed, where possible, there should be unit tests
    demonstrating the bug and also proving the fix. This helps prevent
    regressions.

## Merging pull requests

Maintainers can only merge pull requests after any maintainer, other than the
author of a pull request, has approved the code according to the decision
making process outlined above.

Maintainers must keep pull requests open for at least 24 hours after approval
to merge is given, to allow anyone to voice a concern that may have been missed
in review, or request more time to investigate a suspected issue. If a situation
arises where more time has been requested but cannot be granted, at maintainer
discretion, a new issue or pull request should be opened to address the defect
or discuss improved alternatives. Requests for time and maintainer decision
making are expected to be clearly documented on the pull request discussion on
Github.

Maintenance tasks and time-critical patches can be exempted from this rule if
these are clearly marked as such, at maintainer discretion.

## Copyright

By contributing to this repository, you agree to license your work under the
GNU Affero General Public License version 3 unless specified otherwise at the
top of the file itself.

By default, any contributions automatically assign copyright to the
Free Software Foundation, Inc (FSF) unless the you opt to partially assign
copyright to yourself with a comment underneath the line that assigns to FSF:

```
Portions Copyright (C) Year Your Name <Your@Email>
```

For more information why it may be beneficial to simply assign to the FSF,
see http://www.gnu.org/licenses/why-assign.html

Any work contributed where you are not the original author must contain its
license header with the original author(s) and source.

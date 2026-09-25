# gittuf Contributor ladder

gittuf's contributor ladder is loosely inspired by the OpenSSF [Scorecard
Contributor Ladder]. This document details how community members may advance to
more-involved roles within the gittuf project.

- [Roles](#roles)
    - [Community members](#community-members)
    - [Maintainers](#maintainers)
- [Inactive members](#inactive-members)

## Roles

### Community members

Community members engage with gittuf, contributing their time and energy in
discussions or just generally helping out.

#### Pre-requisites

- Must follow the [OpenSSF Code of Conduct]
- Must follow the [Contribution Guide]

#### Responsibilities

- Keep it up!

### Reviewers

Reviewers are responsible for reviewing PRs and issues as they are opened. They
assist maintainers by helping to triage newly-opened PRs and issues and ensure
that the contribution is of good quality and valid.

Approval reviews by reviewers do not count towards the approval threshold for a
PR, only reviews from maintainers will count.

**Defined by:** Listed in the `Reviewers` section of `MAINTAINERS.txt` file in
the project repository

#### Pre-requisites

- Helped to review submissions to the codebase (e.g., provided genuine reviews
  on 5 PRs that were merged to the codebase)
- Be invited by a maintainer of the project

#### Responsibilities

- Demonstrate sound technical judgment
- Review pull requests as they are opened
- Participate in gittuf community meetings, if possible

#### Promotion process

- Must be nominated by a maintainer
    - With no objections from other maintainers
    - Done through PR to update the `MAINTAINERS.txt` file

### Maintainers

Maintainers are responsible for the project's overall health. They are the only
ones who can approve and merge code contributions.

**Defined by:** Listed in the `Maintainers` section of  `MAINTAINERS.txt` file
in the project repository

#### Pre-requisites

- Provided substantial improvements to the codebase (e.g., adding 5 substantial
  PRs to the codebase)
- Helped to review other substantial submissions to the codebase (e.g., provided
  genuine reviews on 10 PRs that were merged to the codebase)
- Participated as part of the reviewers group as defined above

#### Responsibilities

- Demonstrate sound technical judgment
- Maintain project quality control via code reviews
- Be responsive to review requests
- Mentor contributors
- Participate in gittuf community meetings, if possible
- Facilitate gittuf community meetings, as is needed

#### Promotion process

- May self-nominate or be nominated by a maintainer
    - With no objections from other maintainers
    - Done through PR to update the `MAINTAINERS.txt` file
    - In case of nomination, nominating maintainer must comment approval on the
      PR

## Inactive members

A core principle in maintaining a healthy community is encouraging active
participation. It is inevitable that a contributor's focus will change over time
and there is no expectation they'll actively contribute forever.

Any contributor at any level described above may write an issue (or PR, if
`MAINTAINERS.txt` changes are necessary) asking to step down to a lighter-weight
tier or to depart the project entirely. Such requests will hopefully come after
thoughtful conversations with the rest of the team and with sufficient
forewarning for the others to prepare. However, sometimes "life happens".
Therefore, the change in responsibilities will be understood to take immediate
effect, regardless of whether the issue/PR has been acknowledged or merged.

However, should a Reviewer or Maintainer be deemed inactive for a significant
period, any Community Member or above may write an issue/PR requesting their
removal from the ranks (and `@mentioning` the inactive contributor in the hopes
of drawing their attention). The request must receive support (in comments) from
a majority of Maintainers to proceed.

In all cases, the reviewer's or maintainer's entry in `MAINTAINERS.txt` file
will be updated to reflect their emeritus status.

[OpenSSF Code of Conduct]: /CODE-OF-CONDUCT.md
[Contribution Guide]: https://github.com/gittuf/gittuf/blob/main/CONTRIBUTING.md
[Scorecard Contributor Ladder]: https://github.com/ossf/scorecard/blob/main/CONTRIBUTOR_LADDER.md

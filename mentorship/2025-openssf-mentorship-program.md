# 2025 OpenSSF Mentorship Program - gittuf

Dates: June 2 - August 29

## Purpose

gittuf is a security layer for Git repositories, allowing for a security policy
to be applied independently of the service the repository may be hosted on (e.g.
GitHub, Gitlab, Bitbucket, etc…). The purpose of this project is to improve
gittuf in several domains, such as functionality, usability, and ease of access
for new users.

## Goal
Build a tool to help with visualization of gittuf’s metadata: gittuf uses
metadata inspired by The Update Framework (TUF). While there is functionality in
gittuf to examine its metadata, a visualization tool would help with
understanding how gittuf’s metadata is structured, especially for new users and
complex policies.

Enable temporary/time-limited approvals: There may be cases when a developer may
need to exercise some discretionary authority and approve something in violation
of the policy (e.g. a critical security patch at 4am may not be able to be
approved by the full team required in policy). Adding approvals that will
satisfy the policy for some duration of time (but not infinitely) would serve to
improve this aspect of gittuf.

## Desired Outcomes & Deliverables (1 mentee)

### Build a tool that visualizes gittuf’s metadata

The end goal of this project is to make it easier for users to understand how a
policy is defined for some repository by way of a visual tool.

The tool should be ideally hostable on the web and, given a link to a
repository, produce an interactive graph with similar information to the diagram
here, but with more detail. Ideally, a user unfamiliar with how gittuf works
should be able to more or less understand the trust hierarchy in a repository
and who must approve changes to which changes.

Support for private repositories is also a goal of this project, so users should
be either to upload repository metadata (e.g. the tool suggests commands to run
and upload the results) or also have the tool run on the desktop and locally
ingest repositories.

#### Deliverables

- A web-based tool (that ideally also runs on desktop) that allows users to select
a repository and visualize its gittuf metadata.
- Supporting documentation for how to use the tool.
- [Stretch goal] Policy verification simulator for proposed changes.

### Add functionality to gittuf to enable temporary/time-limited approvals

Some changes in a repository may need to violate the policy (e.g. a critical
security patch needing to be released at 4am, and only one developer is
available to approve changes at the time).

A variant of this feature is to allow for changes to be submitted to a
repository that must still be reviewed by someone else at a later time. These
changes should not be consumed until they are reviewed, but should not
necessarily pose a problem for the repository’s policy.

#### Deliverables

- A new feature that enables temporary/time-limited approvals in gittuf, as described above.
- Supporting documentation for how to use this new functionality in gittuf.
- Sufficient tests to ensure the proper operation of this new feature.

## Relevant Knowledge & Recommended Skills

### All projects

#### Skills

- Writing unit tests
- Documentation best practices

#### Technologies
- Git
- Go
- TUF

### Web visualization tool

#### Skills

- Web development skills 

#### Technologies

- Knowledge of a modern web framework (e.g. Vue or React)
- HTML/CSS/JS

## Mentors

- Patrick Zielinski (patrick.z@nyu.edu)
- Aditya Sirish A Yelgundhalli (aditya.sirish@nyu.edu)

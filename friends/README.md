# Friends of gittuf

This file contains a record of adoptions or integrations of gittuf that we know
about.

We welcome any adopters or integrators of gittuf to open a pull request to add
their adoption of gittuf to the list below.

## Adoptions of gittuf

Adoption and integration of gittuf can take multiple forms, in addition to
adopting gittuf itself to protect a repository.

### gittuf GitHub App

The [gittuf GitHub App](https://github.com/gittuf/github-app) performs actions
automatically to ease integrating gittuf with GitHub. The app can be deployed
in a lite mode where an RSL is created to start recording changes, or in a full
mode to enforce a policy. Pull request approvals from users are captured and
made available to gittuf to enforce policy.

## Adoptions and Integrations

| Adopter / Integration | Description | Links |
| - | - | -|
| Entire | Entire is a Git forge, and has deployed gittuf's RSL. Full gittuf deployment is a work-in-progress. | [1](https://entire.com/blog/secure-your-repositories-with-reference-state-logs), [2](https://github.com/entireio/entire-rsl#quickstart) |
| SLSA | Supply-chain Levels for Software Artifacts (SLSA)'s Source Track defines multiple levels for software source security practices. gittuf can be used to enforce compliance with the SLSA Source Track, and compatibility with the SLSA sourcetool is forthcoming. | [1](https://slsa.dev/spec/latest/source-requirements), [2](https://github.com/slsa-framework/source-tool)|
| Obsidian Systems | The `daml` package ecosystem currently has no centralized infrastructure; plans are underway to, among other things, use gittuf to protect the distribution repositories. | [1](https://github.com/canton-foundation/canton-dev-fund/blob/main/proposals/2026-07-Obsidian-Package-Distribution.md) |

## Credit

gittuf Friends is inspired from similar ideas in the software supply chain
space, such as TUF, in-toto, Sigstore, and tektoncd.
# wadhwani: verification and operations

Reviewed against [default-branch commit cf0594ba2263](https://github.com/noel-ult/wadhwani/commit/cf0594ba2263e7a19e5f5475cc56e27d191a0ea5) on 2026-10-28. Start with the [developer guide](../README.md) for installation and architecture, and the [source reference](REFERENCE.md) for exact scripts, configuration readers, routes, and source locations.

## Concept landing page

Check the problem/solution sections, contact anchor, buttons, and responsive layout. Confirm public wording describes the current concept accurately.

These are acceptance scenarios for a maintainer to run in the documented environment. Their inclusion is not a claim that live integrations or production credentials were tested during this documentation update.

## Deployment and failure diagnosis

Deploy index.html as static content. Credit assessment and account/data integrations require future implementation.

## Maintaining the contract

When behavior changes, update the guide and examples in the same PR. Check the entry point and working directory before copying commands. Use the linked source readers to distinguish build-time configuration from process environment. For failures, capture the first application error, runtime version, selected mode, and redacted configuration names before later proxy or port errors.

Keep changes tied to evidence: a declared command is not proof it passes, a process health response is not a successful end-to-end workflow, and a historical report describes its own revision. Record actual check results and any unavailable external services in the PR.

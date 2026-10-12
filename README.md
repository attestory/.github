# attestory/.github

<!-- atlas:context generated-from factory.yaml -->
Purpose: the organisation's public face on the forge; today profile/README.md only, no shared workflow or template yet. Governed by hand. Ledger: git history.
Organisation: [attestory](https://github.com/attestory).
<!-- /atlas:context -->

The organisation profile remains in `profile/README.md`. This root document
describes the repository itself and does not replace or render that profile.

## Factory floor

The pinned common floor is Contracts at
`afd5223e185a7fb4c7eb6242a54b720530e43c51`. This repository selects no native
stack and declares no required CI lane. Its recorded hand road and silent-main
reason remain in `factory.yaml`; adoption does not introduce a recurring workflow.

For a reviewed change, check out that exact catalog revision and run its composite
action's local entry point against this repository:

```sh
node /path/to/contracts/.github/actions/stack-floor/index.mjs /path/to/this/repository
```

The check refuses an unreadable Git object store before its whole-history secret
scan. Workflow checks apply when workflows exist; today there are none. Do not
describe absent native or workflow checks as a zero-diagnostic native build.
Review the change through the repository's PR road, verify the forge signature,
and replay the same pinned floor at the landing before recording it green.

Qualification on 2026-10-12 at base
`d88745259540f1a5b646c38015e5263630ef8d30`: all four history commits were readable,
the common scan found no leaks, and the selected empty stack set passed. A matched
warm Linux ARM64 replay was green before 0.295s/70008832 anonymous bytes and after
0.266s/76627968 bytes, with 4 CPU/4GiB and 200ms sampling. Acquisition and auth are
excluded; no native-build or hosted pair is claimed. The catalog's planted-secret,
workflow and unknown-stack refusal tests remain its shared red/green evidence.

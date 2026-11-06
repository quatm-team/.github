# Contributing to Quatm

Thanks for taking the time to improve Quatm. This organization hosts
organization-wide GitHub defaults; the framework source, issue tracker and
release process live with the relevant product repository or are coordinated
through the Quatm team.

## Before you start

- **Questions and usage help:** see [SUPPORT.md](SUPPORT.md) or the
  [documentation](https://quatm.com/en/docs/).
- **Bugs and feature proposals:** use the issue templates in this repository
  unless the target repository provides its own.
- **Security issues:** do **not** open a public issue. Follow
  [SECURITY.md](SECURITY.md).
- **Commercial licensing or collaboration:** contact
  [sales@quatm.com](mailto:sales@quatm.com).

For substantial changes, open an issue first so the design and licensing
boundary can be agreed before implementation.

## Contribution workflow

1. Describe the problem and the smallest useful change.
2. Add or update tests and documentation with the change.
3. Run the repository's checks before requesting review. In a framework
   checkout this is:

   ```bash
   scripts/check.sh
   ```

4. Keep pull requests focused. Separate refactors, behaviour changes and
   formatting-only edits.
5. Update user-facing documentation when an interface, default or workflow
   changes.

## Code and documentation standards

- Follow the conventions already used by the target package; do not introduce
  a second style for a local change.
- Do not add dependencies without an ADR explaining the reason and the
  alternatives considered.
- Do not commit credentials, private laboratory data, device serial numbers,
  network addresses or unredacted experiment files.
- Keep scientific units and timing semantics explicit. Do not change timing,
  unit or persistence semantics silently.
- Public documentation should state what is verified, not what is merely
  planned.

## Licensing of contributions

Quatm uses a split licence:

- Contributions to the AGPL-3.0-covered core are accepted under AGPL-3.0.
- Contributions to commercial/proprietary components require a separate
  written agreement with the Quatm team.
- By submitting a contribution, you confirm that you have the right to license
  it on these terms.

If you are unsure which boundary applies, ask before opening the pull request.

## Review

Maintainers review for correctness, test coverage, operational safety,
documentation and licence compatibility. A pull request may be declined when
it adds maintenance cost without a clear laboratory use case, or when it
crosses a licensing boundary without agreement.

## Conduct

Participation is covered by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

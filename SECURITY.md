# Security policy

Quatm controls laboratory hardware and can affect physical equipment. Please
report suspected vulnerabilities privately and give the team time to
investigate before public disclosure.

## Reporting a vulnerability

Email **security@quatm.com** with:

- affected component and version/commit;
- a short description of the impact;
- reproduction steps or a minimal proof of concept;
- relevant logs or configuration, with secrets and laboratory identifiers
  removed;
- whether the issue is already public or under active exploitation.

Do **not** open a public GitHub issue, discussion or pull request for a
vulnerability. If you are unsure whether something is security-sensitive,
report it privately first.

The public security policy is also available at
<https://quatm.com/en/security-policy/>.

## Response

The team aims to acknowledge reports within **24 hours** and will coordinate a
fix and disclosure timeline with the reporter. Response and remediation times
depend on severity, reproducibility and the affected release line.

## Supported versions

Security fixes are prioritised for the current supported release line. Older
releases may receive best-effort guidance only. Include the exact version in
your report; if you are unsure, include the output of the application's
About/version page.

## Scope

In scope includes the Quatm experiment runtime, servers, GUI, web console,
licensing components and shipped device drivers.

Out of scope includes:

- vulnerabilities in third-party instruments, vendor SDKs or operating-system
  packages that Quatm does not control (report them to the vendor as well);
- laboratory network misconfiguration that is not caused by a Quatm default;
- social engineering and physical access attacks;
- reports that require access to a system the reporter is not authorised to
  test.

Please act responsibly: do not access data, move equipment, or disrupt an
experiment while testing. Stop and contact the team if a test could affect
hardware safety.

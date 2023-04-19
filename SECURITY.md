# Reporting security issues

We're extremely grateful to security researchers and users
who report vulnerabilities to WireMock and its ecosystem.
All reports are thoroughly investigated by maintainers of respective repositories.

## When to report issues?

- You think you discovered a potential security vulnerability in WireMock or its components
- You are unsure how a publicly announced vulnerability in an upstream project affects WireMock,
  and you suspect users might be impacted.
- You think you discovered a new vulnerability in another project that WireMock depends on.
  If so, make sure to report the issue to that project too by following their guidelines

Note that security hardening enhancements are not considered vulnerabilities,
and the common Request for Enhancement issue report should be used.

## How to report an issue?

Most of WireMock repositories use the _GitHub Security Advisory_ engine
under the _Security_ tab for issue reporting.
Use it to submit the vulnerability reports,
and only maintainers will be able to see and triage your reports.
They will contact you to negotiate the disclosure time and the next steps.

If you cannot use the GitHub reporting flow or if you didn't get a response within one week,
you can also email the private `conduct@wiremock.org` list with the security details and the details expected for the bug reports.
It is not the main intent of this channel, but the security issues will be routed too.

For upstream projects and WireMock components with their own vulnerability reporting and disclosure process,
please follow those processes.

## Public Disclosure Timing

A public disclosure date is negotiated by WireMock maintainers and the bug submitter.
We prefer to fully disclose the bug as soon as possible once a user mitigation is available in WireMock and in downstream projects and distributions.
Note that it might take some time to coordinate releases and announcements 
even after the fix is available.
The WireMock maintainers will coordinate that.

The timeframe for disclosure is from immediate (especially if it's already publicly known) to a few months.
We intend to release fixes no later than 3 months according to the current independent security research practices.
We urge reporters to not disclose issues in public channels and social media before that.

## Acknowledgements

This guide is inspired by the
[Jenkins Security Policy](https://jenkins.io/security),
[Kubernetes Security and Disclosure Information Guide](https://kubernetes.io/docs/reference/issues-security/security/),
and the [InnerSource pattern on security](https://github.com/InnerSourceCommons/InnerSourcePatterns/blob/main/patterns/1-initial/balancing-openness-and-security.md).


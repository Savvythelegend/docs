# Security Policy
We are very grateful to the security researchers and users who report
Layer5 project security vulnerabilities. We investigate every report thoroughly.

## Reporting a vulnerability
To make a report, send an email to the private
[security-vulns-reports@layer5.io](mailto:security-vulns-reports@layer5.io)
mailing list with the vulnerability details. For normal product bugs
unrelated to latent security vulnerabilities, please head to
the appropriate repository and submit a [new issue](../../issues/new/choose).

### When to report a security vulnerability?

Send us a report whenever you:

- Think Layer5 projects have a potential security vulnerability.
- Are unsure whether or how a vulnerability affects Layer5 projects.
- Think a vulnerability is present in another project that Layer5 projects
depend on (Docker, for example).

### When not to report a security vulnerability?

Don't send a vulnerability report if:

- You need help tuning Layer5 project components for security.
- You need help applying security-related updates.
- Your issue is not security-related.

## Evaluation

The Layer5 team acknowledges and analyzes each vulnerability report within 10 working days.

Any vulnerability information you share with the Layer5 team stays
within the Layer5 project. We do not disseminate the information to other
projects. We only share the information as needed to fix the issue.

We keep the reporter updated on the status of the security issue as it is addressed.

## Fixing the issue

Once a security vulnerability has been fully characterized, a fix is developed by the Layer5 team.
The development and testing for the fix happen in a private GitHub repository in order to prevent
premature disclosure of the vulnerability.

## Early disclosure

The Layer5 team maintains a mailing list for private early disclosure of security vulnerabilities. 
The list is used to provide actionable information to trusted Layer5 partners. The list is not intended 
for individuals to find out about security issues.

## Public disclosure

On the day chosen for public disclosure, a sequence of activities takes place as quickly as possible:

- Changes are merged from the private GitHub repository holding the fix into the appropriate set of public
branches.
- The Layer5 team ensures all necessary binaries are promptly built and published.
- Once the binaries are available, an announcement is sent out on the following channels:
  - The [Layer5 blog](https://layer5.io/blog/)
  - The [Layer5 Twitter feed](https://twitter.com/layer5)
  - The #announcements channel on Slack

As much as possible, this announcement will be actionable and include any mitigating steps customers can take prior to
upgrading to a fixed version.

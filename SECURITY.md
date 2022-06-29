# Security Policy

Paketo Buildpacks provides a single point of contact for the reporting of security vulnerabilities in our codebases and coordinates the process of investigating any reports. Please limit notifications to those vulnerabilites that are not already disclosed publicly or belong to software that is owned by Paketo Buildpacks. To notify of vulnerabilites in other software impacting Paketo Buildpacks codebases, please file an issue in the impacted codebase.

**Please do not ever disclose a security vulnerability for the first time in a public forum**

## Prerequisites

* [ ] Has this security vulnerability been publicly disclosed already?
    - If **Yes**, there's no need to proceed. If you have follow up questions or concerns, you may open a standard bug issue against corresponding project.
    - If **No**, please proceed.

* [ ] Is this a vulnerability in a dependency installed by the buildpack?
    - If **Yes**, then **STOP**, you need to open an issue with the upstream project following their security policy. Paketo Buildpacks will pick up the fix when upstream has made it available.
    - If **No**, please proceed.

* [ ] Is this a vulnerability detected by a scanner against a buildpack build/run image, stack, or buildpack generated image?
    - If **Yes**, then [please read this first](https://paketo.io/docs/concepts/stacks/#when-are-paketo-stacks-updated). If it does not address your concern, please continue.
    - If **No**, please proceed.

## Report a Vulnerability

We strongly encourage people to report security vulnerabilities privately to our security team before disclosing them in a public forum.

The e-mail address to use is **security@lists.paketo.io**.

Please note that the e-mail address above should only be used for reporting undisclosed security vulnerabilities in open source Paketo Buildpacks codebases and managing the process of fixing such vulnerabilities. We cannot accept regular bug reports or other security-related queries at this address.

If you wish to send encrypted email, our public key can be obtained from a public key server such as keys.openpgp.org. The fingerprint is: `3DAE AB7E 64A8 05DC 0538  FF7E A24D 7559 B7C9 D390`

### What to Include

1. Describe your Concern. Provide a summary of your concern. Include CVE numbers, if they exist.
2. Steps to Reproduce. Provide a link to an reproduction/test case, or an unambiguous set of steps to reproduce this vulnerability. Include notes about the software versions you're using, the environment in which you're running, code snippets to reproduce, log output, screenshots, etc..
3. Possible Solution. Not obligatory, but suggest an acceptable fix for the vulnerability.
4. Impact. Within the context of buildpacks, what is the impact of the vulnerability? How could it be missued? Providing context helps us come up with a solution that best resolves the issue.
5. Any additional context or information around the issue you deem relevant.

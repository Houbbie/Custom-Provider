<!--
Thanks for contributing. These scripts are samples provided as is, without
warranty. Do not include real credentials, tokens or secrets anywhere in this
pull request (code, logs, screenshots).
-->

## What does this change

<!-- A short description of the change and the motivation. -->

## Type of change

- [ ] New platform provider
- [ ] Enhancement to an existing provider
- [ ] Bug fix
- [ ] Documentation only
- [ ] Test harness / tooling

## Related issues

<!-- e.g. Closes #123 -->

## Validation status

- [ ] Tested against a live system (state the platform and version below)
- [ ] Sample only, not validated against a live system

<!-- Platform and version, PowerShell version, RAS version if relevant: -->

## General checklist

- [ ] Script parses with no errors (`Parser::ParseFile`, see CONTRIBUTING section 5)
- [ ] No credentials, tokens or secrets committed; secrets handled as secure variables
- [ ] TLS validation defaults to on; any certificate-check skip is an opt-in, documented setting
- [ ] Nothing written to stdout except one JSON response per request (logs go to a file)
- [ ] Documentation updated (provider README and/or root README as needed)
- [ ] PR is focused; the provider folder is self-contained

## New provider checklist

<!-- Only for a new platform provider. Copy the full "New provider checklist"
from CONTRIBUTING.md and tick each item, or delete this section if not applicable. -->

- [ ] Completed the [New provider checklist](../blob/main/CONTRIBUTING.md#new-provider-checklist)

---

By submitting this pull request I confirm my contribution is licensed under the
[MIT License](../blob/main/LICENSE) and I agree to the
[Code of Conduct](../blob/main/CODE_OF_CONDUCT.md).

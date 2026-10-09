# Security Policy

## Supported versions

| Version | Supported |
| --- | --- |
| 0.1.0 | Yes |

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

Report it privately through GitHub: go to the repository's **Security** tab and click **Report a vulnerability** ([direct link](https://github.com/nncast/googlewebdesign-storybook/security/advisories/new)).

Include:

- the version, and the page or file that is affected
- the steps to reproduce, and the browser you used
- what an attacker could do with it

You should get a reply within 7 days. Once the problem is confirmed, a fix is released as a new version and you are credited in the release notes unless you prefer not to be.

## Scope

Dinner With Grandpa is a static storybook that runs in the browser. It has no server, no accounts and stores no data.

- **In scope:** the source document `Storybook_Demo.html` and the browser builds in `gwd_preview_Storybook_Demo/` and `Storybook_Demo/`.
- **Out of scope:** the Google Web Designer runtime files (`gwd*_min.js`, `gwd*_style.css`) and Google Fonts. Report problems in those to Google.

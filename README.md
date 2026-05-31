# Echo Isle Official

Official public repository for Echo Isle / 声屿, a focused podcast player for iOS.

This repository hosts the public product website, legal documents, support pages, and community feedback workflows for Echo Isle.

## Links

- Website: https://echoisle.microspotlight.team
- Privacy Policy: https://echoisle.microspotlight.team/privacy
- Terms of Use: https://echoisle.microspotlight.team/terms
- Support: https://echoisle.microspotlight.team/support
- Feedback and issues: https://github.com/MicroSpotlight/EchoIsle-Official/issues
- Discussions: https://github.com/MicroSpotlight/EchoIsle-Official/discussions

## Repository Structure

```text
docs/
  CNAME                 Custom domain for GitHub Pages
  index.md              Website home page
  privacy.md            Privacy Policy
  terms.md              Terms of Use
  support.md            Support and feedback
  content-rights.md     Podcast content and rights policy
  data-and-security.md  Data, storage, and network behavior
  changelog.md          Public release notes
.github/
  ISSUE_TEMPLATE/       GitHub issue forms
  DISCUSSION_TEMPLATE/  Discussion templates
  CODE_OF_CONDUCT.md
  CONTRIBUTING.md
  SECURITY.md
```

## GitHub Pages

Pages is served from the `docs/` directory on the `main` branch.

Custom domain:

```text
echoisle.microspotlight.team
```

## Product Summary

Echo Isle is an RSS-based podcast client. It can discover shows through podcast search, import public RSS feeds, play episodes in the background, remember playback progress, and download episodes for personal offline listening.

Echo Isle does not require an account and does not include ads or tracking-oriented SDKs.

## Maintenance Notes

- Keep public legal and support pages in `docs/`.
- Keep feedback workflows in `.github/ISSUE_TEMPLATE/`.
- Update `docs/changelog.md` for each public App Store release.
- When app behavior changes around data, networking, downloads, analytics, accounts, or third-party services, update `docs/privacy.md` and `docs/data-and-security.md` before release.

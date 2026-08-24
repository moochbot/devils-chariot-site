# Devil's Chariot — public pages

The privacy policy and support page for the [Devil's Chariot](https://apps.apple.com/)
iPhone app, served at
[moochbot.github.io/devils-chariot-site](https://moochbot.github.io/devils-chariot-site/).

These are the URLs given to App Store Connect. They live here rather than on the
app's own web deployment because Apple checks them during review, and a hosting
account that can block a build is a bad dependency for a URL a reviewer has to
be able to load.

## Do not edit the HTML

Every page here is generated. The source is `docs/privacy-policy.md` and
`docs/support.md` in the main (private) repository. Edit those, then regenerate:

```bash
node scripts/publish-site.mjs ../devils-chariot-site
```

and commit the result here.

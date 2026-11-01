# GameMonster: privacy policy and support

The public pages for the GameMonster iPhone app, served by GitHub Pages:

- Privacy Policy: https://indxneo.github.io/gamemonster-legal/privacy/
- Support: https://indxneo.github.io/gamemonster-legal/support/

These are the App Store's "Privacy Policy URL" and "Support URL", and the app links to both from
Settings › About.

**Don't edit the HTML here.** It's generated from the Markdown in the app's (private) repository,
`docs/legal/PRIVACY.md` and `docs/legal/SUPPORT.md`, by its `tools/build-legal.ts`:

```sh
# in the gamemonster checkout, with this repository cloned next to it
node tools/build-legal.ts ../gamemonster-legal
```

Then commit and push here; GitHub Pages publishes within a minute or two.

## Android

The Android app has its own pages (Google backup and Google's on-device tools instead of iCloud and
Apple Intelligence), the Play Store's privacy policy URL and the Android app's Settings links:

- Privacy Policy: https://indxneo.github.io/gamemonster-legal/android/privacy/
- Support: https://indxneo.github.io/gamemonster-legal/android/support/

They're generated the same way from the Android app's (private) repository,
`github.com/indxneo/gamemonster-android`: `docs/legal/*.md` → `tools/build-legal.ts`, which writes
only `android/` and reuses this site's `style.css` and `icon.png`. The iPhone tool never touches
`android/`.

```sh
# in the gamemonster-android checkout, with this repository cloned next to it
node tools/build-legal.ts ../gamemonster-legal
```

Contact: alishersv.dev@outlook.com

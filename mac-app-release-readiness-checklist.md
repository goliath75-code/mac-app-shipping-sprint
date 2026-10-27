# Mac App Release-Readiness Checklist

A practical, no-account-access checklist for independent Mac app makers preparing a first customer-facing release.

## 1. Build and launch

- [ ] Build from a clean checkout using documented commands.
- [ ] Confirm the app launches on a Mac that has not previously run it.
- [ ] Test the key customer flow, not only the happy path.
- [ ] Check that the app name, version, and icon are correct.
- [ ] Record the macOS versions and hardware tested.

## 2. Package

- [ ] Create a repeatable archive, disk image, installer, or ZIP process.
- [ ] Ensure the customer gets only the intended files.
- [ ] Include clear install and uninstall instructions.
- [ ] Verify the download opens and extracts cleanly.

## 3. Trust and security

- [ ] Decide whether Developer ID signing and notarization are required for this release.
- [ ] Keep certificates, API keys, and passwords in the owner’s control.
- [ ] Never embed secrets in the app or its repository.
- [ ] Confirm any network requests use HTTPS and have a clear privacy purpose.

## 4. Customer experience

- [ ] Write a one-paragraph description of the app and who it is for.
- [ ] State the price, trial terms, or beta terms plainly.
- [ ] Add a support email or contact method.
- [ ] Create a short troubleshooting section for first-launch problems.
- [ ] Test the first-run experience with someone who did not build the app.

## 5. Release day

- [ ] Tag or record the exact source revision that produced the release.
- [ ] Keep a copy of the shipped artifact and its checksum.
- [ ] Publish concise release notes.
- [ ] Confirm the public download and contact links work.
- [ ] Decide how you will receive and track customer feedback.

## Want a second set of eyes?

I offer a free 15-minute release-readiness audit for working Swift/SwiftUI, Electron, Tauri, and Python-based Mac apps. The goal is to identify the few things that could block a confident release.

See the [Mac App Shipping Sprint](https://goliath75-code.github.io/mac-app-shipping-sprint/) or email [goliath75@icloud.com](mailto:goliath75@icloud.com).

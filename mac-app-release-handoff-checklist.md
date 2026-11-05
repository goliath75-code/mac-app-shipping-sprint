# Mac App Release Handoff Checklist

Use this after the build is working and before telling customers it is ready.

## 1. Build identity
- [ ] Confirm the version and build number shown to customers.
- [ ] Build the exact archive intended for distribution.
- [ ] Verify the app bundle’s name, icon, and metadata outside the project folder.

## 2. Signing and security
- [ ] Sign the final app with the intended distribution identity.
- [ ] Check entitlements against the features actually used.
- [ ] Test the signed build after copying it to a clean folder.
- [ ] If distributing outside the App Store, complete notarization and staple the final artifact where appropriate.

## 3. Customer installation path
- [ ] Download the final artifact as a customer would.
- [ ] Move it to Applications (or follow the chosen install flow).
- [ ] Launch it from the installed location, not from a build or project folder.
- [ ] Repeat on a clean macOS user account or another Mac.

## 4. First launch
- [ ] Confirm every permission prompt appears only when it is needed.
- [ ] Check that privacy and permission explanations make sense to a non-developer.
- [ ] Test quit, relaunch, update, and basic recovery from an interrupted first run.
- [ ] Make the next customer action obvious: create, import, connect, or start.

## 5. Handoff
- [ ] Save the release archive, version notes, and install instructions in one place.
- [ ] Record the signing, notarization, and smoke-test results.
- [ ] Keep a short known-issues list and a repeatable checklist for the next release.

> This checklist reduces avoidable release risk. It is not an App Store approval or notarization guarantee.

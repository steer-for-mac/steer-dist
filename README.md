# steer-dist

Release artifacts for [Steer](https://steer.seanfloyd.dev): notarized DMGs and the
Sparkle appcast. **Private until launch** -- flip to public so the cask `url` and
Sparkle update downloads resolve for end users.

- GitHub Releases hold each `Steer.dmg` (Developer-ID signed, notarized, stapled).
- The Sparkle appcast is served from the marketing site
  (`steer.seanfloyd.dev/appcast.xml`); its `enclosure url` points at the release
  asset here.
- Produced by `just release-direct` + `generate_appcast` in the main repo.

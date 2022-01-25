---
name: New Flatcar Release
about: Tracking issue for releasing a new Flatcar major version.
title: 'Release Flatcar Container Linux <VERSION> [<VERSION>] [...]'
labels: "kind/release"
assignees: '@sayanchowdhury'
---

## Release Flatcar Container Linux <Alpha-VERSION> [<Beta-VERSION>] [>Stable-VERSION>]
  
The release of Flatcar Container Linux <VERSION> [<VERSION> ...] is planned for <MONTH> <DAY>, <YEAR>. 

### Tasks
- [ ] Go / No Go tracking folder created, tracking doc added ()
- [ ] All planned changes are merged & blocker bugs are fixed ()
- [ ] Branch off main (only new major) ()
- [ ] Tag build branch ()
- [ ] Generate manifest ()
- [ ] Start Jenkins builds ()
- [ ] Test status captured in test status tracker ()
- [ ] Create SDK container after Jenkins is done building the flatcar-sdk tarball; upload container to ghcr.io
- [ ] All tests are green ()
- [ ] Archive TAP report, create Go / No Go doc ()
- [ ] Release notes / announcements added to Go/No Go doc ()
- [ ] QA: check diff for image file list, packages, and image size ()
- [ ] Matrix Go/No Go meeting (inc. release notes review) ()
- [ ] Manifest release created on GitHub ()
- [ ] Update the SDK release metadata for new major Alpha releases with SDK builds (only new major) ()
- [ ] Images uploaded ()
- [ ] Run the `os/release` job ()
- [ ] Publish EC2 Marketplace Images (Submit for scanning) ()
- [ ] Publish EC2 Marketplace Images (Update Product) ()
- [ ] Azure offer updated & publishing started ()
- [ ] Azure Go Live ()
- [ ] GCP offers updated ()
- [ ] Update payload signed/published ()
- [ ] Symlink to "current" updated ()
- [ ] Website updated ()
- [ ] Update CloudFormation templates ()
- [ ] Release package published in Nebraska ()
- [ ] Send announcement to Mailing Lists, and tweet out! (@miao0miao, @ahrkrak)

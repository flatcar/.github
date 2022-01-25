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
- [x] Go / No Go tracking folder created, tracking doc added ()
- [x] All planned changes are merged & blocker bugs are fixed ()
- [x] Branch off main (only new major) ()
- [x] Tag build branch ()
- [x] Generate manifest ()
- [x] Start Jenkins builds ()
- [x] Test status captured in test status tracker ()
- [x] All tests are green ()
- [x] Archive TAP report, create Go / No Go doc ()
- [x] Release notes / announcements added to Go/No Go doc ()
- [x] QA: check diff for image file list, packages, and image size ()
- [x] Matrix Go/No Go meeting (inc. release notes review) ()
- [x] Manifest release created on GitHub ()
- [x] Update the SDK release metadata for new major Alpha releases with SDK builds (only new major) ()
- [x] Images uploaded ()
- [x] Run the `os/release` job ()
- [x] Publish EC2 Marketplace Images (Submit for scanning) ()
- [x] Publish EC2 Marketplace Images (Update Product) ()
- [x] Azure offer updated & publishing started ()
- [x] Azure Go Live ()
- [x] GCP offers updated ()
- [x] Update payload signed/published ()
- [x] Symlink to "current" updated ()
- [x] Website updated ()
- [x] Update CloudFormation templates ()
- [x] Release package published in Nebraska ()
- [x] Send announcement to Mailing Lists, and tweet out! (@miao0miao, @ahrkrak)

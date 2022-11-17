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
- [ ] Go / No Go [hackmd doc](https://hackmd.io/team/flatcar?nav=overview) created from previous one for test tracking and release notes: [link](TODO) ()
- [ ] All planned changes are merged & blocker bugs are fixed, last nightly reviewed for problems ()
- [ ] Branch off main (only new major) ()
- [ ] Tag build branch ()
- [ ] Start Jenkins builds, post links as comment ()
- [ ] Test status captured in hackmd doc ()
- [ ] All tests are green ()
- [ ] Release notes / announcements added to Go/No Go doc from `container/image_changes` job by selecting `Timestamps: None` ()
- [ ] QA: check diff for image file list, packages, and image size in the image job output ()
- [ ] Matrix Go/No Go meeting (inc. release notes review) ()
- [ ] Update payload signed/uploaded ()
- [ ] `scripts` release created on GitHub ()
- [ ] Release job `container/release` ran ()
- [ ] Images uploaded with `copy-to-origin.sh` ()
- [ ] Azure offer updated & publishing started ()
- [ ] Azure Go Live ()
- [ ] GCP offers updated ()
- [ ] Symlink to "current" updated with `set-symlink.sh` ()
- [ ] Website updated with `./update-flatcar-versions.sh` and PR merged ()
- [ ] Release package published in Nebraska ()
- [ ] Send announcement to Mailing Lists ()
- [ ] Send Tweet out (@miao0miao, @ahrkrak)
- [ ] Brief version announcement in slack (k8s slack #flatcar) and the Flatcar matrix channel

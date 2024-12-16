---
name: New Flatcar Release
about: Tracking issue for releasing a new Flatcar major version.
title: 'Release Flatcar Container Linux <VERSION> [<VERSION>] [...]'
labels: "kind/release"
assignees: '@sayanchowdhury'
---

The release of the following Flatcar Container Linux version is planning <MONTH> <DAY>, <YEAR>.

- Alpha <VERSION>
- Beta <VERSION>
- Stable <VERSION>
- LTS <VERSION>

## 1. Preparation

Owner:

- [ ] A. Go/No-Go [hackmd doc](https://hackmd.io/team/flatcar) created from HackMD template for test tracking and release notes: (update the link here)
- [ ] B. All planned changes are merged & blocker bugs are fixed, last nightly reviewed for problems.
- [ ] C. Check that the kernel PR are merged for the channel(s) to be released.

## 2. Build

Owner:

- [ ] A. Branched off the `main` branch (only for new major).
- [ ] B. Tagged all the build branches.
- [ ] C. Started the Jenkins builds, post the links into this issue as comment.


## 3. Release

### i. The Go/No-Go Meeting

Owner:

- [ ] A. Test status captured in the HackMD document.
- [ ] B. All tests are Green.
- [ ] C. Release notes / announcements added to Go/No Go doc from `container/image_changes` job by selecting `Timestamps: None`.
- [ ] D. QA: Checked the diff for image file list, packages, and image size in the `container/image_changes` job output.
- [ ] E. Conduct Matrix Go/No Go meeting (inc. release notes review).


### ii. Artifacts goes public

Owner:

- [ ] A. Ran the `container/release` Release job.
- [ ] B. Created the Release Notes on the `scripts` repo for the respective tags on GitHub as GitHub Releases.
- [ ] C. Images uploaded with `copy-to-origin.sh`.
- [ ] D. Symlink to "current" updated with `set-symlink.sh`.
- [ ] E. Website updated with `./update-flatcar-versions.sh` and PR merged.

### iii. Payload

Owner:

- [ ] A. Update payload signed/uploaded.
- [ ] B. Release package published in Nebraska (Prerequisite: 3.ii.E should marked done).

### iv. Cloud Marketplace & Cluster API

Owner:

- A. Azure
    - [ ] Offers updated and started publishing.
    - [ ] Sent the offers to publish to Live.

- B. GCP
    - [ ] Offer deployment package uploaded to Google Bucket & submit for verification.
    - [ ] Offer Publish

- C. Cluster API for new Stable
  - [ ] Azure: Manually run `./azure-sig.sh` to create New Shared Community Gallery Images
  - [ ] OpenStack: [documentation](https://gist.github.com/tormath1/acbae5c6cd12420bb8ea137e25655c99)

## 4. Announcements

Owner:

- [ ] A. Sent announcement to Mailing Lists
- [ ] B. Sent Tweet out to X (Twitter), and Toot out to Mastodon
- [ ] C. Brief version announcement in slack (k8s slack #flatcar) and the Flatcar Matrix channel

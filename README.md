<h1 align="center">
  <img src="https://genopro.com/images/GenoProHeader2016.png" alt="GenoPro">
</h1>

<p align="center"><b>This is the snap for <a href="https://genopro.com">GenoPro</a></b>, <i>“The best genealogy software for drawing family trees and genograms.”</i> It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>


<p align="center">
<a href="https://snapcraft.io/genopro">
  <img alt="genopro" src="https://snapcraft.io/genopro/badge.svg" />
</a>
<a href="https://snapcraft.io/genopro">
  <img alt="genopro" src="https://snapcraft.io/genopro/trending.svg?name=0" />
</a>
</p>

![genopro](Screenshot.webp?raw=true "genopro")

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" alt="Linux" /> with 💝 by Snapcrafters</p>

## Install

To install this snap, run

    sudo snap install genopro
    
from your terminal. This will install a GenoPro application icon, and upon first run it will automatically download and install the appropriate Visual C runtime for wine and GenoPro.

Please note that you will need Internet access on the first run of the application.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/genopro)

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Additional tools

The snap also makes the commands `genopro.wine` and `genopro.winetricks` available. The former allows one to run Windows executables in the GenoPro wine environment and the latter allows use of winetricks within that same environment.

## Remaining tasks
![genopro](images/Basic.png?raw=true "genopro")


Snapcrafters ([join us](https://forum.snapcraft.io/t/snapcrafters-reboot/24625)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml) upstream so GenoPro can authoritatively publish future releases.

  - [x] Click the green "Use this template" button above to create a new repository based on this template
  - [x] Give the newly created repository a sensible name, like `godzilla` if you're snapping the Godzilla software (*Note: Do not use `snap` in this name.*)
  - [x] Update the description of the repository to `Unofficial snap for [Project]`
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [x] Post a call for testing in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link](https://forum.snapcraft.io/t/call-for-testing-genopro/32962)
  - [ ] Add the Snapcraft store account (snap-advocacy@canonical.com) as a collaborator to your snap in the [Dashboard](https://dashboard.snapcraft.io) and ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to accept this request
  - [ ] Fix all important issues found during testing
  - [ ] Make a post in the Snapcraft Forum ["store-requests" category](https://forum.snapcraft.io/c/store-requests/19) asking for a transfer of the snap name from you to Snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Ask upstream if they are interested in maintaining the Snap. If they are:
    - [ ] Fork the upstream project, add the snap build files and required assets/launchers to that repo and submit a pull request or patch - [link]()
    - [ ] Add upstream contact information to the `README.md`
    - If upstream accept the PR:
      - [ ] Request upstream create a Snap store account
      - [ ] Add upstream account as a collaborator on the snap
      - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![Alex Lowe](https://avatars.githubusercontent.com/u/4305943?v=4)](https://github.com/lengau/) |
| :---: |
| [Alex Lowe](https://github.com/lengau/) |

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->

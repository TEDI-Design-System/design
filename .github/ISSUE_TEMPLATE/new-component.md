---
name: New component
about: Designing new TEDI component
title: '[Component name]'
labels: 'New component'
assignees: ''

---

## Design
- Follow Figma practices:
  - [ ] Asset uses **variables** _(spacing, padding, colors, sizes etc)_ and styles _(shadows, typography)_ - has dark mode and/or desktop/tablet/mobile variables
  - [ ] All the frames are named according to semantic meaning
  - [ ] All the variants, states, colours, types are displayed on the Figma frame
  - [ ] All the extra examples are shown below, after the component
  - [ ] All text and other attributes are under Properties so the user can switch things on and off and change texts from property section
  - [ ] Check that the asset **does not have any errors** in the properties
  - [ ] Check the name of the asset, if it's clear and clean - sync with dev team
  - [ ] Add link and thumbnail to table of contents page in Figma
  - [ ] Resolve all the comments
  - [ ] Add documentation section - _includes links to Storybook (React and/or Angular) and Zeroheight_
  - [ ] Add **Status badges** if its ready in design, React or/and Angular - _on top of the frame: ✓ Documentation, ✓ Figma, ✓ React, ✓ Angular_
  - [ ] Add informative badges _(frame header)_:
    - [ ] If it's detachable _(optional)_ - _meaning you can detach the component and adjust it using variables_ 
    - [ ] If it's tested against WCAG AA level
    - [ ] If it's only design component etc
  - [ ] Add **variant level status properties** ("//Angular dev: done/not done" and "//React dev: done/not done") - _statuses are removed after the component variant is developed in both_
  - [ ] Check if component needs a **Tips and Tricks section** - _instruction section which includes extra notes if there's something design specific other designers should know_
- General rules:
  - [ ] Component has **dark mode** examples
  - [ ] Component has **passed WCAG AA** test in Figma -> Use the right Github column for that, assign to the right person
  - [ ] Is tested by another designer - _design review: short texts, long texts, property naming etc - usability of the component for designers_ -> Use the right Github column for that, assign to the right person
  - [ ] Is **responsive or adaptive**, is tested on small and large device - _if needed mobile version is created_

Component is published if:
  - [ ] Asset is published in Figma file, _add correct notes what was changed_
  - [ ] Add description to Release notes table - what changed or if it's initial release then what is improved
  - [ ] **Figma version no** is updated - _Figma version update [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_

More things to do:
  - [ ] **Close design task** in Github
  - [ ] Add tasks to dev board (React and Angular separately)
  - [ ] Add ZH task to Design board or if it's small thing - add it immediately to ZH
  - [ ] Update [statuses page in Zeroheight](https://tedi.tehik.ee/1ee8444b7/p/300e17-komponentide-staatused)

Monthly things:
  - [ ] Figma new version is **published to the Figma community** - _Change version number manually, it does not change automatically_

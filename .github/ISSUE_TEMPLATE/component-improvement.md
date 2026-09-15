---
name: Component design improvement
about: Designing new TEDI component
title: '[Component name]: ..'
labels: 'component improvement'
assignees: ''

---
Improvement need description: 

## Design
- Follow Figma practices:
  - [ ] Asset uses **variables** _(spacing, padding, colors, sizes etc)_ and styles _(shadows, typography)_ - has dark mode and/or desktop/tablet/mobile variables
    - [ ] All created variables matches with previous logic
  - [ ] All the frames are named according to semantic meaning
  - [ ] All added variants, states, colours, types are displayed on the Figma frame
  - [ ] All the extra examples are shown below, after the component
  - [ ] All text and other attributes are under Properties so the user can switch things on and off and change texts from property section
  - [ ] Check that the asset **does not have any errors** in the properties
  - [ ] Resolve all the comments
  - [ ] Add **variant level status properties** ("//Angular dev: done/not done" and "//React dev: done/not done") - _statuses are removed after the component variant is developed in both_
  - [ ] Check if component needs a **Tips and Tricks section** - _instruction section which includes extra notes if there's something design specific other designers should know_
- General rules:
  - [ ] Improvement has **passed WCAG AA** test in Figma -> Use the right Github column for that, assign to the right person
  - [ ] Is tested by another designer - _design review: short texts, long texts, property naming etc - usability of the component for designers_ -> Use the right Github column for that, assign to the right person
  - [ ] Is **responsive or adaptive**, is tested on small and large device

Component improvement is published if:
  - [ ] Asset is published in Figma file, _add correct notes what was changed_
  - [ ] Add description to Release notes table - what changed
  - [ ] **Figma version no** is updated - _Figma version update [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_

More things to do:
  - [ ] **Close design task** in Github
  - [ ] Create tasks to dev board (React and Angular separately if those are not already created)
  - [ ] Create ZH improvement task to Design board or if it's small thing - add it immediately to ZH

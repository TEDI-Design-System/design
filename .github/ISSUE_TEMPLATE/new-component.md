---
name: New component
about: Designing new TEDI component
title: ''
labels: ''
assignees: ''

---

## Design
- [ ] Component is designed using best practices:
  - [ ] Relies on **TEDI variables** _(spacing, padding, colors, sizes etc)_ and styles _(shadows, typography)_
    - [ ] Create semantic variables if needed
  - [ ] **Different variants** are created according to the needs
  - [ ] Has **dark theme**
  - [ ] Has **passed WCAG AA** test in Figma
  - [ ] Is tested by another designer - _**design review**: short texts, long texts, property naming etc - usability of the component for designers_
  - [ ] Is **responsive or adaptive**, is tested on small and large device - _if needed mobile version is created_
  - [ ] Is technically up to date according to new Figma features
- [ ] Component has following statuses:
  - [ ] **Status badges** if its design, React component or/and Angular component is ready - _on top of the frame: ✓ Figma, ✓ React, ✓ Angular_
  - [ ] **Informative badges** _(frame header)_:
    - [ ] If it's detachable _(optional)_ - _meaning you can detach the component and adjust it using variables_ 
    - [ ] If it's tested against WCAG AA level
    - [ ] If it's documented
  - [ ] **Ready for dev** _(built in Figma status)_ - _if it's not yet developed in both React and Angular_
  - [ ] **Variant level status properties** ("//Angular dev: done/not done" and "//React dev: done/not done") - _statuses are removed after the component variant is developed in both_
- [ ] Component has a **Documentation section** - _includes links to Storybook (React and/or Angular) and Zeroheight_
- [ ] Component has a **Tips and Tricks section** - _instruction section which includes extra notes if there's something design specific other designers should know_
- [ ] Component is published:
  - [ ] **In Figma file** - _library publish for the TEDI-Ready Figma file, add correct notes what was changed_
  - [ ] **Figma version is updated** - _Figma version update [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_
  - [ ] Figma version is **saved manually to file history** - _Add version and notes what changed_
  - [ ] Figma version is **published to the Figma community** - _Change version number manually, it does not change automatically_
  - [ ] Add link that refers to the component to Figma **table of contents**
  - [ ] **Close design task** in Github
  - [ ] **Create dev tasks** about the component to Github kanban board (both React and Angular) 
  - [ ] **Add changes to release notes draft** in Zeroheight _- release notes is published once a month_
  - [ ] Clean component from comments _(optional)_ 
  - [ ] Add component specific **release notes** time and notes to the footer of the frame in Figma
  - [ ] Update [statuses page in Zeroheight](https://tedi.tehik.ee/1ee8444b7/p/300e17-komponentide-staatused)

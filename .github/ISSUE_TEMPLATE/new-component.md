---
name: New component
about: Designing new TEDI component
title: '[Component name]'
labels: 'new component'
assignees: ''

---

## Design
Building in Figma
- Use [this page](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=53464-194001) to create new component
- Important: Do no publish the component before all the checkboxes are done.
- [ ] Component has _ prefix inserted before the name so that it will not be published and is hidden until it is ready.
- [ ] Asset uses **semantic variables**
  - colors light/dark + desktop/tablet/mobile variables
  - naming and logic can be seen from previous variables
  - use cross reference, for example: number field input is created -> see what other form fields are using -> create new number input variables and refer to other form field variables or use general form field variables. The idea is that if the next designr decides to change form field border colour then all related form border colours are changed at once - baseline is that all related colours should be related actually in variables also
  - variables shoul not have spaces
  - variables should start with a small letter
  - states should have separate variables, see previous logics
- [ ] Figma display
    - [ ] All the variants, states, colours, types are displayed on the Figma frame
    - [ ] Follow Figma component display [structure](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=61857-217602&t=z9Im7ct4SH7TwxRA-4), add tips and tricks where needed, check if all the statuses are up to date
- [ ] All the frames are named according to semantic meaning, for example no Frame342453 should be left in
- [ ] Properties are Capitalized, first letter is uppercase others are not, for example: Show closing button
- [ ] All text and other attributes are under Properties so the user can switch things on and off and change texts from property section
- [ ] Check that the asset **does not have any errors** in the properties
- [ ] Check the name of the asset, if it's clear and clean - sync with dev team
- [ ] Is **responsive or adaptive**, is tested on small and large device - _if needed mobile version is created_
Finishing up
- [ ] Move component to the right location in the file
- [ ] Add link and thumbnail to table of contents page in Figma
- [ ] Resolve all the comments
- [ ] Add **variant level status properties** ("//Angular dev: done/not done" and "//React dev: done/not done") - _statuses are removed after the component variant is developed in both_

Send te design to the reviewers, can be sent to multiple reviewers at once if needed.

## Dev review
1. After design is ready add Figma link to Github task
2. Move it to Review column in Github
3. Assign it to dev team member

_It is important that dev team approves the component name, checks if all the states are designed, component is placed under logical page and folder, all variables are correct, design does not have things that are not possible to do in development or is not logical to do
_

## Design review
1. After design is ready add Figma link to Github task
2. Move it to Review column in Github
3. Assign it to design team member

_design review: short texts, long texts, property naming etc - usability of the component for designers_

## WCAG review
1. After design is ready add Figma link to Github task
2. Move it to Review column in Github
3. Assign it to WCAG team member

## For publisher
Component is published if:
  - [ ] Asset is published in Figma file, _add correct notes what was changed_
    - [ ] Component name: what changed -> **publish only this component not all the file at once**
  - [ ] Add description to Release notes table, under the component - what changed or if it's initial release then what is improved
  - [ ] **Figma version no** is updated - _Figma version update [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_
  - [ ] **Close design task** in Github
  - [ ] Add tasks to dev board (React and Angular separately)
  - [ ] Add ZH task to Design board or if it's small thing - add it immediately to ZH
  - [ ] Update [statuses page in Zeroheight](https://tedi.tehik.ee/1ee8444b7/p/300e17-komponentide-staatused)

## For release
See here under design section: https://github.com/TEDI-Design-System/general/issues/19 

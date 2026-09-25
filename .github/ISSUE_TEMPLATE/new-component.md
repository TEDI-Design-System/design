---
name: New component
about: Designing new TEDI component
title: '[Component name]'
labels: 'new component'
assignees: ''

---

## 1. Design
Building in Figma
- Use [this page](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=53464-194001) to create a new component.
- Important: Do not publish the component until all checkboxes are ticked.
- [ ] The component name has an _ prefix, so it stays unpublished and hidden until it's ready.
- [ ] Asset uses **semantic variables**
  - colours: light/dark + desktop/tablet/mobile variables
  - follow the naming and logic of existing variables
  - use cross-references. For example, when creating a number field input, check what other form fields use, then create new number input variables that refer to other form field variables or to general form field variables. This way, if a designer later changes the form field border colour, all related border colours change at once. The rule: colours that are related should also be linked in variables
  - variable names must not contain spaces
  - variable names must start with a lowercase letter
  - each state has its own variables (follow existing logic)
- [ ] Figma display
    - [ ] All variants, states, colours and types are shown on the Figma frame
    - [ ] Follow the Figma component display [structure](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=61857-217602&t=z9Im7ct4SH7TwxRA-4), add tips and tricks where needed and check that all statuses are up to date
- [ ] All frames have semantic names, e.g. no Frame342453 is left
- [ ] Figma properties
  - [ ] Properties use sentence case (only the first letter is uppercase), e.g. Show closing button
  - [ ] All texts and other attributes are in Properties, so users can toggle things on and off and edit texts in the Properties section
  - [ ] Check that the asset's properties **have no errors**
- [ ] Check that the asset name is clear and clean - agree on it with the dev team
- [ ] Is **responsive or adaptive** and tested on small and large devices - _create a mobile version if needed_

Finishing up
- [ ] Move the component to the right place in the file
- [ ] Add a link and thumbnail to the table of contents page in Figma
- [ ] Resolve all comments
- [ ] Add **variant-level status properties** ("//Angular dev: done/not done" and "//React dev: done/not done") - _remove the statuses once the variant has been developed in both_

Send the design to reviewers. If needed, you can send it to several reviewers at once.

## 2. Design review
1. When the design is ready, add the Figma link to the GitHub task
2. Move it to the Review column in GitHub
3. Assign it to a design team member

_Design review: short texts, long texts, property naming etc. - how usable the component is for designers_

## 3. Dev review
1. When the design is ready, add the Figma link to the GitHub task
2. Move it to the Review column in GitHub
3. Assign it to a dev team member

_The dev team must approve the component name and check that all states are designed, the component is on a logical page and in a logical folder, all variables are correct, and the design contains nothing that is impossible or illogical to build._

## 4. WCAG review
1. When the design is ready, add the Figma link to the GitHub task
2. Move it to the Review column in GitHub
3. Assign it to a WCAG team member

## 5. For publisher
The component is published when:
  - [ ] The asset is published in the Figma file, _with correct notes on what changed_
    - [ ] 'Component name: what changed' -> **publish only this component, not the whole file at once**
  - [ ] Add a description to the Release notes table under the component: what changed, or for an initial release, what was improved
  - [ ] **Figma version no** is updated - _update the Figma version [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_
  - [ ] **Close the design task** in GitHub
  - [ ] Add tasks to the dev board (React and Angular separately)
    - 'New TEDI-READY component' -> Repository: TEDI-Design-system/react
    - 'New TEDI-READY component' -> Repository: TEDI-Design-system/angular
  - [ ] Add a ZH task to the Design board, or if it's a small change, add it to ZH right away
  - [ ] Update the [statuses page in Zeroheight](https://tedi.tehik.ee/1ee8444b7/p/300e17-komponentide-staatused)

## For release
See here under design section: https://github.com/TEDI-Design-System/general/issues/19 

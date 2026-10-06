---
name: New TEDI-Ready component
about: New TEDI component
title: '[Component name]'
labels: 'new component'
assignees: ''

---

## Figma 

Figma design: _add link here_

_________
Component creation process:
1. A need (from [Discussions](https://github.com/orgs/TEDI-Design-System/discussions), from dev team, from design meeting, from TEDI team etc)
2. **Design task created** in Design board 
3. **Figma design** is made 
4. Dev/**design**/WCAG **reviews** 
5. **Design in published/released in Figma** 
6. Dev tasks are created to [dev board](https://github.com/orgs/TEDI-Design-System/projects/7/views/1?filterQuery=) (separate tasks for angular, react, vue) **and** Zeroheight task is created to Design board
7. Component is developed **and** Zeroheight documentation is created
8. **Design**/Code/WCAG **review** 
9. Component is released in development (Angular, React separately)
10. Monthly release is made, fill Zeroheight release notes and **fill the checklist** under [Figma section](https://github.com/TEDI-Design-System/general/issues/19)
11. After release, **update Figma statuses and add Storybook links** according the [after release checklist](https://github.com/TEDI-Design-System/general/issues/19)
_________

## 1. Design
Building in Figma
- Use [this page](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=53464-194001) to create a new component.
- **Important**: Do not publish the component until all checkboxes are ticked.
- [ ] The component name has an _ prefix, so it stays unpublished and hidden until it's ready.
- [ ] Asset uses **semantic variables**
  - colours: light/dark + desktop/tablet/mobile variables
  - follow the naming and logic of existing variables.
  **For Example**: _button/primary/background/hover_ -> in development the same variable will be exported as _--button-primary-background-hover_
  - use cross-references. For example, when creating a number field input, check what other form fields use, then create new number input variables that refer to other form field variables or to general form field variables. This way, if a designer later changes the form field border colour, all related border colours change at once. The rule: colours that are related should also be linked in variables
  - variable names must not contain spaces, **For example**: _secondary-inverted not secondary inverted_
  - variable names must start with a lowercase letter, **For example**: _button/secondary/border/hover not Button/Secondary/Border/Hover_
  - each state has its own variables, follow existing logic, **For example**: 
    - _button/floating/primary/background/default_
    - _button/floating/primary/background/hover_
    - _button/floating/primary/background/active_
    - _button/floating/primary/background/focus_
    - _button/floating/primary/background/disabled_
- [ ] Figma display
    - [ ] All variants, states, colours and types are shown on the Figma frame
    - [ ] Follow the Figma component display [structure](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.76.92?node-id=61857-217602&t=z9Im7ct4SH7TwxRA-4), add tips and tricks where needed and check that all statuses are up to date
- [ ] All frames have semantic names, e.g. no Frame342453 is left. **For example**: _Container, Left slot, Right slot, Heading, Title, Actions_ etc
- [ ] Figma properties
  - [ ] Properties use sentence case (only the first letter is uppercase). **For example**: _Closing button: True/False, Variant: Primary/Secondary, Size: Default/Small etc_
  - [ ] All texts and other attributes are in Properties, so users can toggle things on and off and edit texts in the Properties section
  - [ ] Check that the asset's properties **have no errors**
- [ ] Check that the asset name is clear and clean - agree on it with the dev team, it is breaking change to change the name later in dev
- [ ] Is **responsive or adaptive** and tested on small and large devices - _create a mobile version if needed_

Finishing up
- [ ] **Move the component to the right place** in the file, check with dev team what is the suitable folder/section and page (in dev it is breaking change to change the location later). Zeroheight, Figma and Storybook components are following the same hierarchy. 
- [ ] Add a **link and thumbnail** to the [table of contents page](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.78.100?node-id=42478-115025&t=yLPTW7XTo84isNNP-4) in Figma
- [ ] Resolve all comments
- [ ] Add **variant-level status properties**
  - //Angular dev: done/not done
  - //React dev: done/not done
  -  Remove/change the statuses once the variant has been developed in both [during monthly release](https://github.com/TEDI-Design-System/general/issues/19)

Send the design to reviewers. If needed, you can send it to several reviewers at once.

## 2. Design review
_Action is done in the same issue, on the [Design board](https://github.com/orgs/TEDI-Design-System/projects/2/views/7)._
1. When the design is ready, add the Figma link to the GitHub issue 
2. Move it to the **Review column** in GitHub
3. Assign it to a design team member

_Design review: short texts, long texts, property naming etc. - how usable the component is for designers_

## 3. Dev review
_Action is done in the same issue, on the [Design board](https://github.com/orgs/TEDI-Design-System/projects/2/views/7)._
1. When the design is ready, add the Figma link to the GitHub task
2. Move it to the **Review column** in GitHub
3. Assign it to a dev team member

_The dev team must approve the component name and check that all states are designed, the component is on a logical page and in a logical folder, all variables are correct, and the design contains nothing that is impossible or illogical to build._

## 4. WCAG review
_Action is done in the same issue, on the [Design board](https://github.com/orgs/TEDI-Design-System/projects/2/views/7)._
1. When the design is ready, add the Figma link to the GitHub task
2. Move it to the **Review column** in GitHub
3. Assign it to a accessibility specialist 

## 5. For publisher
The component is published when:
  - [ ] The asset is published in the Figma file, **publish only this component, not the whole file at once**, with correct notes on what changed. **For example**:
    - _Timeline:_ 
        - _Initial release_
  - [ ] **Add date and description to the Release notes** table under the component (on the Figma frame)
  - [ ] **Figma version no** is updated - _update the Figma version [according to the rules](https://www.figma.com/design/jWiRIXhHRxwVdMSimKX2FF/TEDI-READY-2.15.25?node-id=14930-122933&t=tV6tckof7HQ6o9Cq-4)_
      - Do not change the first number
      - Change the middle number if something visual has changed, for example: new variant is added, new property is added, new color is added, new state is added etc
      - Change the last number if something is fixed or change is non-visual, for example: variable name changes, icon position was fixed, something missing was brought back etc
      - After every fix change the Figma version number and **save the Figma version to file history**
  - [ ] Figma file is saved to history with short description what was changed, do it every time after you change the version number, for example:
      - _Title: ver 2.56.99_
      - _Description: Timeline, Attachment added, Number filed improvements_
  - [ ] **Close the design task** in GitHub if all the reviews are done 
  - [ ] Add tasks to the [Development board](https://github.com/orgs/TEDI-Design-System/projects/7/views/1?filterQuery=) (React and Angular separately)
    - Check if there already are dev tasks, search by component name or check storybook Main branch ([react](https://storybook.tedi.ee/react/main/?path=/docs/documentation-welcome--welcome), [angular](https://storybook.tedi.ee/angular/main/?path=/docs/documentation-welcome--welcome)) or Figma statuses, if not developed then create new tasks.
    - If new variant is added in design and dev team has not developed the component at all then add task just for new component. If component is already developed and new variant is added in design then add TEDI-Ready issue that refers what has changed/added so dev team would understand what needs to be added to existing component. 
        - 'New TEDI-READY component' or 'TEDI-Ready issue' -> Repository: TEDI-Design-system/react
        - 'New TEDI-READY component' or 'TEDI-Ready issue' -> Repository: TEDI-Design-system/angular
  - [ ] Add a ZH task to the Design board, or if it's a small change, add the info to ZH right away
  - [ ] Update the [statuses page in Zeroheight](https://tedi.tehik.ee/1ee8444b7/p/300e17-komponentide-staatused)
  - [ ] Check if the component is related to any of the [Discussions](https://github.com/orgs/TEDI-Design-System/discussions), if yes then close the discussion with a comment that includes infot about the component being designed. 

## For release
  - [ ] Fill the checklist of the last comment (under **Figma** section): https://github.com/TEDI-Design-System/general/issues/19 

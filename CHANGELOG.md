## v2.0.3

- Bug fixing: prevent applying normalize() to template pages HTML as it can break Vue behavior (only Vue3)
- Dependencies upgrade

## v2.0.2

- Fixing the contenteditable field highlight to the Invoice Template of the Demo
- Adding back Vue2 syntax to the basic example

## v2.0.1

- Workaround for the Chrome "return from print" bug. Now displays a return arrow to let the user go back to the editor when this bug happens.

## v2.0.0

- Switching `master` branch to Vue3 (we provide vue2 compatibility on the vue2 branch / @1.x version of this library)
- Dependencies upgrade

## v1.2.6

- Workaround for the Chrome "return from print" bug. Now displays a return arrow to let the user go back to the editor when this bug happens.

## v1.2.5

- Fix [Issue 11](https://github.com/motla/vue-document-editor/issues/9): Using editable prop to provide read only view

## v1.2.4

- Removing pages manually from the DOM now remove corresponding items from the `content` you provide
- Adding `data-page-idx` to pages `<div>`s for custom user scripts convenience
- \[Demo\] Add dynamic page break functionality example (still experimental)
- \[Demo\] Restrict nb of table lines in the invoice template page, fix CSS for printing

## v1.2.3

- Removing useless surrounding `<div>`s from the synchronized document content
- Fix content synchronizing from an empty content array
- Fix content update was not triggered after some of the `executeCommand` functions
- \[Demo\] Reset the history stack after new document creation
- Dependencies upgrade

## v1.2.2

- Fix [Issue 4](https://github.com/motla/vue-document-editor/issues/4): problem with ?. operator

## v1.2.1

- Force white page background when printing

## v1.2.0

- Adding `overlay` functionality and documentation
- Enable printing of CSS background colors/image
- Dependencies upgrade

## v1.1.2

- Fix [Issue 3](https://github.com/motla/vue-document-editor/issues/3)
  - Renaming the static library "VueDocumentEditor"
  - Adding UMD example to README.md

## v1.1.1

- Bugfix [Issue 2](https://github.com/motla/vue-document-editor/issues/2): Enter key to create new line doesn't seem to work on the demo site
- Bugfix: restoring a new document when user wipes out the entire document

## v1.1.0

- Undo/Redo mechanism moved to Demo.vue in order to let custom implementation in application
- Bugfix: preserving text selection when calling `execCommand`
- Minor display improvements in the Demo about scrollbars
- Better overall compatibility for Firefox

## v1.0.0

Initial release
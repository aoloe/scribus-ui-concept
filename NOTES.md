# Notes

## Palettes, windows, dialogs


### Current situation

Scribus has not a clearcut separation §

- Windows that manage resources (fonts, master pages, colors, ...):
  - Are in the "Edit" menu.
  - Are mostly modal (the document cannot be edited while their open).
  - Are floating.
  - Each window is the only way for editing the specific resource.
- Dialogs that provide actions on the document and its items (align and distribute, arrange pages, scrapbook, ...):
  - Are in the "Windows" menu
  - Are non modal (the document can be edited while their open)
  - Are floating.
  - They can only be opened through the menu entry.
- Dialogs that modify the properties of items (property palette)
  - Are in the "Windows" menu.
  - Are non modal.
  - Can be floating or docked to side.
  - They can only be opened through the menu entry.
- Dialogs for standard actions (new, open, pdf export, ...)
  - Are in the "File" menu.
  - Are modal.
  - Are floating.
  - They can only be opened through the menu entry.

Roundoup:

- The menus are the only way you can discover a feature.
- The features can only be used through one specific way.
- Many features require full focus (modal dialogs).
- 

### Proposal

Each dialog should be filled under one of three categories:

- Resource management
- Properties palettes
- Tools
- Actions

#### Resource management

Interaction:
-
-

Interface:

- Resources listing and editing should be separated.
- Everywhere a resource is used, it should be possible to create new entries and edit existing ones.

#### Properties palettes

Interaction:

- 

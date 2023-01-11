# Atomic Design 🌀

This project follows the atomic design methodology to build reusable and modular UI components and organize them in a sustainable way.

---

## Atoms ⚛️
Basic building blocks of the user interface, usually not useful on their own.
- Examples: buttons, text inputs, form labels, icons
- Should be small, simple and independent components
- Should only have basic HTML tags and class names, no hooks.

## Molecules 🧩
- Complex components made up of several atoms to build functionality
- Examples: forms, cards, modals
- Should be composed of several atoms, but should still be simple enough to be reused
- Should have a specific purpose and function

## Organisms 🌳
Larger, more complex components made up of several molecules
- Examples: headers, footers, navigation menus
- Should have a specific layout and a clear relationship with the other organisms
- Should be reusable, but less likely to be used outside of the context they were created

---

## Guidelines 📋
- If a component can be used in different contexts, it's probably an atom or molecule ♻️

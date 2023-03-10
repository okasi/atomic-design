## Atomic Design π
This project follows the atomic design methodology to build reusable and modular UI components and organize them in a sustainable way.

---

### Atoms βοΈ
Basic building blocks of the user interface. Usually not useful on their own, can be combined to create more complex components.
- Should be small, simple and independent components to be used in different contexts
- Should only have basic HTML tags and styling.
- Can have props for styling changes, but no logic.

Examples of atoms include:
- Profile image π·
- Buttons π
- Input field β¨οΈ
- Heading π°
- Paragraph π
- Icon ποΈ
- Link π
- Label π·οΈ
- Spinner π

<br>

### Molecules π§©
More complex components that are made up of several atoms. They are designed to build functionality by combining atoms.
- Should be composed of several atoms, but should still be simple enough to be reused
- Should have a specific purpose and function
- Should be designed to be reusable across different contexts and variations of the interface

Examples of molecules include:
- Form with several input fields π
- Card with heading and paragraph π
- Search bar with a submit button π
- Notification badge with a counter π
- Testimonial block with image and quote π£οΈ
- Carousel with several items π
- Accordion with click functionality π
- Share button with social media icon π±
- Progress bar with percentage π§

<br>

### Organisms π³
Combinations of atoms and molecules to form organisms that make up a distinct section of an interface
- Should be reusable, but less likely to be used outside of the context they were created
- Should be self-contained and have their own internal logic
- Should be able to function independently and in conjunction with other organisms

Examples of organisms include:
- Navigation menu ποΈ
- Footer π»
- Sidebar π
- Product reviews π
- Checkout flow π³
- Login form π
- Calendar view π
- Map view πΊοΈ
- Pricing table π°

---

### Guidelines π
- If a component can be used in different contexts, it's probably an atom or molecule β»οΈ
- If a component has a specific layout or relationship with other components, it's probably an organism π±
- Name components based on their function and not their appearance π¨
- Test components in different states and with different props to ensure reusability π
- In a components-based framework project (Next.js / SvelteKit), you can use this methodology by creating a `components` directory in your project and creating subdirectories for `atoms`, `molecules`, and `organisms`.

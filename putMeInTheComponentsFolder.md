## Atomic Design 🌀
This project follows the atomic design methodology to build reusable and modular UI components and organize them in a sustainable way.

---

### Atoms ⚛️
Basic building blocks of the user interface. Usually not useful on their own, can be combined to create more complex components.
- Should be small, simple and independent components to be used in different contexts
- Should only have basic HTML tags and styling.
- Can have props for styling changes, but no logic.

Examples of atoms include:
- Profile image 📷
- Buttons 🔘
- Input field ⌨️
- Heading 📰
- Paragraph 📜
- Icon 🗂️
- Link 🔗
- Label 🏷️
- Spinner 🕐

<br>

### Molecules 🧩
More complex components that are made up of several atoms. They are designed to build functionality by combining atoms.
- Should be composed of several atoms, but should still be simple enough to be reused
- Should have a specific purpose and function
- Should be designed to be reusable across different contexts and variations of the interface

Examples of molecules include:
- Form with several input fields 📊
- Card with heading and paragraph 🃏
- Search bar with a submit button 🔍
- Notification badge with a counter 🔔
- Testimonial block with image and quote 🗣️
- Carousel with several items 🚗
- Accordion with click functionality 📜
- Share button with social media icon 📱
- Progress bar with percentage 🚧

<br>

### Organisms 🌳
Combinations of atoms and molecules to form organisms that make up a distinct section of an interface
- Should be reusable, but less likely to be used outside of the context they were created
- Should be self-contained and have their own internal logic
- Should be able to function independently and in conjunction with other organisms

Examples of organisms include:
- Navigation menu 🗂️
- Footer 🔻
- Sidebar 📚
- Product reviews 🛒
- Checkout flow 💳
- Login form 🔐
- Calendar view 📅
- Map view 🗺️
- Pricing table 💰

---

### Guidelines 📋
- If a component can be used in different contexts, it's probably an atom or molecule ♻️
- If a component has a specific layout or relationship with other components, it's probably an organism 🌱
- Name components based on their function and not their appearance 🎨
- Test components in different states and with different props to ensure reusability 🔍
- In a components-based framework project (Next.js / SvelteKit), you can use this methodology by creating a `components` directory in your project and creating subdirectories for `atoms`, `molecules`, and `organisms`.

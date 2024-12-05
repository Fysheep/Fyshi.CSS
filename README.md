# Fyshi.CSS v2.0.0

Fyshi.CSS is a utility-first CSS library designed for rapid development and easy-to-maintain styles. With a focus on lightweight design and powerful utilities, version 2.0.0 introduces breaking changes and new features to enhance usability and maintainability.

---

## What's New in 2.0.0?
Version 2.0.0 introduces several key changes and improvements:
- **Updated Class Naming Conventions**: Simplified and more descriptive names for better readability (e.g., `ta-left` → `text-left`).
- **CSS Variables**: Introduced spacing variables (`--space-xs`, `--space-sm`, etc.) for consistent and scalable design.
- **Improved Flexibility**: Consolidated and enhanced flex utilities (`fsh-1` now includes `min-width` and `min-height`).
- **Responsive Design**: Added responsive considerations and improved scalability.
- **Backward-Incompatible Changes**: Some class names and functionality have been altered. Refer to the changelog for details.

---

## 1. Utility-First Approach

Fyshi.CSS embraces a utility-first philosophy. Each class is narrowly focused on a single property or a small set of related properties. This allows you to build complex layouts and styles directly in your HTML without writing custom CSS. It offers a smaller, simpler alternative to frameworks like Tailwind CSS.

---

## 2. Flexibility and Positioning

The library includes a wide range of classes to manage positioning and layout effectively:

### **Flexbox Utilities**
- `dp-flex`: Enable flexbox.
- `fd-c`: Set flex direction to column.
- `jc-*`, `ai-*`: Align and justify content easily with options like `center`, `start`, `end`, and more.

### **Sizing Classes**
- `expand`: Full width and height of the parent container.
- `w-fc`, `h-fc`: Fit content width and height.
- `w100`, `h100`: Full width or height.
- `mw-0`, `mh-0`: Minimum width or height of 0 for better flex compatibility.

### **Spacing and Gaps**
- `gap-*`: Control spacing between grid or flex items.
- `p-*`, `m-*`: Padding and margin utilities based on spacing variables (`--space-xs`, `--space-sm`, etc.).

---

## 3. Responsive and Consistent Design

Fyshi.CSS provides utilities that adapt well across different screen sizes:
- `expand`: Ensures elements scale properly.
- `w-fc` and `h-fc`: Fit content while maintaining responsiveness.

Consistency is maintained through the use of CSS variables, ensuring predictable spacing and layout behavior.

---

## 4. Visual Customization

The library offers tools for styling and interactivity:
- **Text Styling**: `font-bold` for bold text, `text-underline` for underlined text.
- **Cursor and Selection**: `[clickable]` for pointer cursor, `[no-sel]` for disabling text selection.

---

## 5. Minimal and Lightweight

Fyshi.CSS avoids the complexity and overhead of full-featured frameworks, making it ideal for projects that need quick setup and a small CSS footprint. It delivers just enough utilities to handle common design patterns efficiently.

---

## How to Use Fyshi.CSS

### Installation
Install Fyshi.CSS via npm:
[package link](https://www.npmjs.com/package/fyshi.css)
```bash
npm i fyshi.css
```

### Import in Your Styles
In your CSS entry file:
```css
@import 'fyshi.css';
``````
## Documentation

Refer to the [Fyshi.CSS Documentation](https://github.com/Fysheep/Fyshi.CSS/wiki) for detailed usage examples.

---

## GitHub

Explore the repository, report issues, or join discussions: [https://github.com/Fysheep/Fyshi.CSS](https://github.com/Fysheep/Fyshi.CSS)

---

## Contributing

Got ideas for improvements? Share them in the discussions tab or submit a pull request. Your feedback helps shape Fyshi.CSS!

---

## Changelog

See the full changelog here or refer to the latest updates below:

- 2.0.0: Changed class naming conventions and improved consistency. Refer to the changelog for details on breaking changes.
    
- 1.0.x: Various improvements to the library, including flex utilities, wrapping classes, and text alignment.
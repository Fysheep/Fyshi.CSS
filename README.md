# Fyshi.CSS
## 1. Utility-First Approach

Each class is narrowly focused, often applying just a single CSS property or a small set of related properties. This means you can mix and match these classes in HTML to build complex layouts or styles without needing custom CSS. It’s a similar philosophy to frameworks like Tailwind CSS, though on a smaller and simpler scale.

## 2. Flexibility and Positioning

The file includes classes for positioning elements easily:

      Flexbox Utilities (dp-flex, fd-c, jc-*, ai-*): These classes cover the essentials of flexbox layouts, allowing you to align and justify content in different ways.

      Sizing Classes (w-fc, w100, h100, mw-0, mh-0): Control width, height, and minimum dimensions, making responsive designs simpler.

      Gap and Spacing (gap-*, p-*): Useful for managing spacing between elements or padding within elements.

      Alignment Classes (ta-left, ta-center, ta-right): Text alignment helpers allow for quick adjustments without needing inline styles.
## 3. Responsive and Consistent Design

The toolkit includes utility classes that work well across different viewports. For example:

    Full-width and height classes (expand) ensure elements scale properly.

    fit-content width (w-fc) adapts to content size, preventing overflow or unwanted stretching.

## 4. Visual Customization

    Text and Cursor Control: Classes like fw-bold, underlined, and noselect help control text styling and behavior.

    Interactivity Enhancements: Attributes like clickable make it easy to signify interactive elements.

## 5. Minimal and Lightweight

Since this toolkit avoids a complex setup or large file size (compared to full-featured frameworks), it’s perfect for projects where you want simplicity and quick development without a heavy CSS load. You get just enough utilities to handle common design patterns without the overhead.
How It Helps with Design

By providing a set of predefined classes for layout, spacing, alignment, and interactivity, this package allows for:

    Rapid Prototyping: Quickly assemble layouts by applying utility classes to elements.

    Consistency: Ensure a consistent look and feel across different components without needing to rewrite CSS.

    Viewport Adaptability: The flexibility in sizing and spacing aids in creating layouts that adjust well to different screen sizes.

# How to use:
- in CMD / CLI: `npm i fyshi.css`
- in main.css file: `import fyshi.css`
- [Documentation](https://github.com/Fysheep/Fyshi.CSS/wiki)

## Github:
[https://github.com/Fysheep/Fyshi.CSS](https://github.com/Fysheep/Fyshi.CSS)

Make sure to post improvement ideas into the discussions tab.

# Changelog:

- 1.0.1: Improved Readme
- 1.0.2: -//-
- 1.0.3: expanded css minorly
- 1.0.4: Readme now includes slight oversight + created Wiki Page (no content yet)
- 1.0.5+6: CSS now includes min-(width,height) for flex-shrink; removed z-index classes 
- 1.0.7: Wiki (1.0.0)


<div align="center">

# Nebula UI


![87_2x_shots_so](https://github.com/user-attachments/assets/829d159f-a316-4961-b04d-8c99a60cddda)


![](https://img.shields.io/badge/%20-v1.0.0-8b5cf6?style=for-the-badge&labelColor=1a1429&logo=Github)
![](https://img.shields.io/badge/%20-MIT-8b5cf6?style=for-the-badge&labelColor=1a1429&logo=Github)
![](https://img.shields.io/badge/%20-44KB-8b5cf6?style=for-the-badge&labelColor=1a1429&logo=Github)

**A lightweight, modern CSS framework for building beautiful web interfaces**

[Demo](https://nebula.0x0060.dev) | [Documentation](https://nebula.0x0060.dev/docs) | [GitHub](https://github.com/0x0060/nebulaUI)

</div>

## Features

Nebula UI is a comprehensive CSS framework designed to help developers build beautiful, responsive, and accessible web interfaces. It provides a wide range of components, utilities, and styles that can be easily customized to match your design system.

- **Modern Design System** - Clean, minimal aesthetic with a focus on usability
- **Accessibility First** - Built with WCAG guidelines in mind
- **Fully Responsive** - Works seamlessly on all devices
- **Lightweight** - Minimal CSS footprint with no JavaScript dependencies
- **Multiple Themes** - Dark, light, and custom color themes included
- **Comprehensive Components** - Everything you need to build modern interfaces
- **Utility Classes** - Flexible utility classes for rapid development
- **Well Documented** - Extensive documentation with examples

## Installation

### Direct Download

Download the CSS file directly and include it in your HTML:

```html
<link rel="stylesheet" href="path/to/nebula.css">
```

### CDN

Include Nebula UI directly from a CDN:

```html
<link rel="stylesheet" href="https://nebula.0x0060.dev/lib/nebula.css">
```

## Quick Start

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Nebula UI Project</title>
    <link rel="stylesheet" href="path/to/nebula.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap">
</head>
<body class="dark-theme">
    <header class="navbar-custom">
        <div class="container">
            <a href="#" class="logo">My Project</a>
            <nav>
                <ul class="nav-links">
                    <li><a href="#" class="nav-link active">Home</a></li>
                    <li><a href="#" class="nav-link">About</a></li>
                    <li><a href="#" class="nav-link">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container section">
        <h1>Welcome to My Project</h1>
        <p>This is a starter template using Nebula UI.</p>
        <button class="btn btn-primary">Get Started</button>
    </main>
</body>
</html>
```

## Components

Nebula UI provides a comprehensive set of UI components to build modern web applications.

### Component List

| Component | Description |
|-----------|--------------|
| Buttons | Primary, secondary, outline, and text buttons with various states |
| Cards | Flexible card components with headers, footers, and hover effects |
| Navigation | Navbar, tabs, breadcrumbs, and pagination |
| Forms | Input fields, checkboxes, radio buttons, selects, and more |
| Modals | Customizable modal dialogs with various sizes |
| Alerts | Success, error, warning, and info alert messages |
| Badges | Small status indicators and counters |
| Tooltips | Informative tooltips that appear on hover |
| Accordions | Collapsible content sections |
| Tables | Styled tables with various options |
| Progress | Progress bars and spinners |
| Typography | Headings, paragraphs, and text utilities |

## Themes

Nebula UI comes with multiple built-in themes that can be easily applied by adding a class to the `body` element.

```html
<!-- Dark Theme (Default) -->
<body class="dark-theme">

<!-- Light Theme -->
<body class="light-theme">

<!-- Purple Theme -->
<body class="purple-theme">

<!-- Blue Theme -->
<body class="blue-theme">
```

## Utilities

Nebula UI provides a comprehensive set of utility classes for rapid development.

### Utility Categories

| Category | Description |
|----------|--------------|
| Layout | Flex, grid, positioning, display, and container utilities |
| Typography | Text alignment, size, weight, and decoration utilities |
| Spacing | Margin and padding utilities with various sizes |
| Colors | Text, background, and border color utilities |
| Borders | Border width, style, radius, and color utilities |
| Effects | Shadow, opacity, and transform utilities |
| Animations | Fade, slide, and custom animation utilities |

## Responsive Design

Nebula UI is built with a mobile-first approach and includes responsive utilities for building adaptive layouts.

```html
<!-- Responsive grid example -->
<div class="grid grid-1 md:grid-2 lg:grid-3 gap-4">
    <div class="card">Item 1</div>
    <div class="card">Item 2</div>
    <div class="card">Item 3</div>
</div>
```

## Accessibility

Accessibility is a core principle of Nebula UI. All components are designed with accessibility in mind, following WCAG guidelines:

- Proper contrast ratios for text and interactive elements
- Keyboard navigation support
- ARIA attributes for screen readers
- Semantic HTML structure

## Compatibility

Nebula UI is framework-agnostic and can be used with any JavaScript framework or library:

- Vanilla HTML/CSS/JS
- React
- Vue
- Angular
- Svelte
- And more!

## Documentation

For complete documentation, examples, and API references, visit the [Nebula UI Documentation](https://0x0060.github.io/nebulaUI/docs).

## Browser Support

| Browser | Supported Versions |
|---------|-----------------|
| Chrome | Latest ✅ |
| Firefox | Latest ✅ |
| Safari | Latest ✅ |
| Edge | Latest ✅ |
| Opera | Latest ✅ |
| IE | Not supported ❌ |

## FAQ

### Does Nebula UI require JavaScript?

No, Nebula UI is a pure CSS framework and doesn't require JavaScript to work. However, some interactive components like modals, accordions, and dropdowns will need JavaScript to handle their functionality.

We provide simple JavaScript examples in our documentation for these components, but you're free to implement the functionality using your preferred JavaScript framework or library.

### Can I customize the default theme?

Yes, Nebula UI uses CSS variables (custom properties) for theming, making it easy to customize. You can override the default variables to create your own theme.

```css
:root {
  --primary: #3b82f6;
  --primary-foreground: #ffffff;
  /* Override other variables as needed */
}
```

### Is Nebula UI production-ready?

Yes, Nebula UI is designed for production use and follows best practices for performance, accessibility, and browser compatibility.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

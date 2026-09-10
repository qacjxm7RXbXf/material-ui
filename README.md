# Accessibility

Learn how MUI components are designed with accessibility in mind, and how to build inclusive user interfaces.

## Overview

Accessibility (a11y) is essential for creating web applications that can be used by everyone, including people with visual, auditory, motor, or cognitive disabilities.

MUI components are built to comply with [WCAG 2.1 Guidelines](https://www.w3.org/TR/WCAG21/) and WAI-ARIA standards wherever possible.

## Features

- **Keyboard Navigation**: All interactive elements support standard keyboard shortcuts and focus management.
- **Color Contrast**: Default theme palettes meet WCAG AA contrast ratio requirements (4.5:1 for normal text).
- **ARIA Attributes**: Components include appropriate ARIA roles, states, and properties out of the box.
- **Screen Reader Support**: Semantic HTML markup is used to ensure screen readers accurately convey component state.

## Best Practices

1. **Provide Accessible Labels**: Use `aria-label` or `aria-labelledby` on icon buttons and inputs without visible labels.
2. **Manage Focus**: Ensure modal dialogs and dropdown menus trap focus appropriately when opened and restore focus when closed.
3. **Avoid Color-Only Cues**: Do not rely solely on color to convey state or required fields; include text or icons as secondary indicators.

## Reporting Accessibility Issues

We welcome feedback and contributions! If you encounter an accessibility obstacle when using MUI components, please open an issue on GitHub tagged with `accessibility`.
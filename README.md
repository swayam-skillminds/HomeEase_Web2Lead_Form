# HomeEase Appliances - Thank You Page

A beautiful, modern thank you page for HomeEase Appliances with a reusable theme system.

## Files Structure

```
HomeEase/
├── thank-you.html          # Main thank you page
├── styles/
│   ├── theme.css          # Reusable theme stylesheet
│   └── thank-you.css      # Page-specific styles
└── README.md              # This file
```

## Theme System

The project uses a comprehensive theme system built with CSS custom properties (variables) that can be reused across all pages.

### Key Features

- **CSS Variables**: All colors, spacing, typography, and other design tokens are defined as CSS variables in `styles/theme.css`
- **Responsive Design**: Mobile-first approach with responsive breakpoints
- **Reusable Components**: Buttons, cards, headers, footers, and other UI components
- **Modern Design**: Clean, professional aesthetic suitable for an appliance company
- **Accessibility**: Semantic HTML and proper color contrasts

### Using the Theme on Other Pages

To use this theme on other pages:

1. Include the theme stylesheet:
```html
<link rel="stylesheet" href="styles/theme.css">
```

2. Use the provided CSS classes:
- `.btn`, `.btn-primary`, `.btn-secondary` - Buttons
- `.card` - Card containers
- `.container` - Content containers
- `.header` - Header component
- `.footer` - Footer component

3. Use CSS variables for custom styling:
```css
.my-custom-element {
    color: var(--primary-600);
    padding: var(--spacing-lg);
    border-radius: var(--radius-lg);
}
```

## Color Palette

- **Primary**: Blue shades (`--primary-500` to `--primary-900`)
- **Success**: Green shades (`--success-500` to `--success-700`)
- **Neutral**: Gray shades (`--neutral-50` to `--neutral-900`)

## Customization

All design tokens can be customized by modifying the `:root` variables in `styles/theme.css`:

- Colors: Change `--primary-*`, `--success-*`, `--neutral-*` variables
- Spacing: Adjust `--spacing-*` variables
- Typography: Modify `--font-*` variables
- Shadows: Update `--shadow-*` variables
- Border Radius: Change `--radius-*` variables

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Custom Properties support required
- Responsive design works on mobile, tablet, and desktop


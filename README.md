<img width="580" height="649" alt="image" src="https://github.com/user-attachments/assets/b164cee1-192f-417a-816a-50ed2fcd3201" />
<img width="580" height="649" alt="image" src="https://github.com/user-attachments/assets/6c279c1a-c276-4192-9ab1-b68af36ef5bb" />


# BOGO Shopping Interface

A responsive shopping interface for "Buy One Get One" (BOGO) offers with independent radio button and box selection functionality.

## Features

- **Independent Selection System**: Radio buttons and box expansion work separately
- **Single Box Expansion**: Only one option box can be expanded at a time
- **Dynamic Size/Color Selection**: Dropdown menus for size and color variants
- **Popular Badge**: Highlight most popular options
- **Responsive Design**: Clean, modern interface with Inter font
- **Interactive Elements**: Hover effects and smooth transitions

## File Structure

```
shopping/
├── index.html          # Main HTML structure
├── styles.css          # All styling and layout
└── README.md           # This file
```

## Functionality

### Radio Button Selection
- Click directly on radio buttons to select pricing options
- Radio selection is independent of box expansion
- Selected radio buttons show red accent color

### Box Expansion
- Click anywhere on an option box (except radio button or dropdowns) to expand
- Only one box can be expanded at a time
- Expanded boxes show:
  - Pink border (`#FF6B82`)
  - Light pink background (`#FFF9FA`)
  - Size and color selection dropdowns

### Interactive Elements
- Size and color dropdowns work without affecting box expansion
- Popular badge displays on featured options
- Smooth transitions and hover effects

## Usage

1. Open `index.html` in a web browser
2. Click radio buttons to select pricing options
3. Click on option boxes to expand and view size/color selections
4. Use dropdowns to select size and color variants
5. Click "Add to Cart" to complete selection

## Architecture

### CSS Design System
Built with a comprehensive CSS custom properties system for maximum maintainability and consistency:

**Responsive Design**
- Uses `rem`, `em`, `vw` units instead of fixed `px` values
- Container width: `min(90vw, 28.875rem)` for responsive scaling
- All spacing uses consistent scale: 0.25rem, 0.5rem, 0.75rem, 1rem, etc.

**Color System**
```css
/* Brand Colors */
--primary-color: #FF6B82
--primary-light: #FFF9FA
--hover-color: #ff5252

/* Semantic Colors */
--text-primary, --text-secondary, --text-muted
--border-color, --border-light, --border-lines
--background-light, --white, --black
```

**Typography Scale**
```css
--font-size-large: 1.25rem    /* 20px */
--font-size-medium: 0.875rem  /* 14px */
--font-size-small: 0.75rem    /* 12px */
--font-size-tiny: 0.625rem    /* 10px */
```

**Layout System**
```css
--spacing-xs: 0.25rem   /* 4px */
--spacing-sm: 0.5rem    /* 8px */
--spacing-md: 0.75rem   /* 12px */
--spacing-lg: 1rem      /* 16px */
--spacing-xl: 1.5rem    /* 24px */
```

### Benefits
- **Consistent**: All values derived from systematic scale
- **Maintainable**: Change design tokens in one place
- **Responsive**: Scales naturally across devices
- **Accessible**: Uses relative units that respect user preferences
- **Themeable**: Easy to create variants by modifying CSS variables

## Browser Compatibility

Compatible with all modern browsers that support:
- CSS Grid and Flexbox
- CSS Custom Properties
- ES6 JavaScript features

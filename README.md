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

## Customization

### Colors
- Primary pink: `#FF6B82`
- Light pink background: `#FFF9FA`
- Border gray: `#e9ecef`
- Text colors defined in CSS variables

### Layout
- Container width: `462px`
- Responsive padding and margins
- Inter font family for clean typography

## Browser Compatibility

Compatible with all modern browsers that support:
- CSS Grid and Flexbox
- CSS Custom Properties
- ES6 JavaScript features
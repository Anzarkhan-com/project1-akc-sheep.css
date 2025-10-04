# AKC Sheep CSS - Complete Utility CSS Framework

A comprehensive utility-first CSS framework similar to Tailwind CSS, with all classes prefixed with `akc-` for easy identification and to avoid conflicts.

## Features

### 🎨 **Spacing Utilities**
- **Margin**: `akc-m-0` to `akc-m-64`, `akc-mx-*`, `akc-my-*`, `akc-mt-*`, `akc-mr-*`, `akc-mb-*`, `akc-ml-*`
- **Padding**: `akc-p-0` to `akc-p-64`, `akc-px-*`, `akc-py-*`, `akc-pt-*`, `akc-pr-*`, `akc-pb-*`, `akc-pl-*`

### 🏗️ **Layout Utilities**
- **Flexbox**: `akc-flex-*`, `akc-justify-*`, `akc-items-*`, `akc-flex-row`, `akc-flex-col`
- **Grid**: `akc-grid-cols-1` to `akc-grid-cols-12`, `akc-gap-*`, `akc-col-span-*`, `akc-row-span-*`
- **Position**: `akc-static`, `akc-relative`, `akc-absolute`, `akc-fixed`, `akc-sticky`
- **Width/Height**: `akc-w-*`, `akc-h-*`, `akc-min-w-*`, `akc-max-w-*`, `akc-min-h-*`, `akc-max-h-*`

### 📝 **Typography Utilities**
- **Text Alignment**: `akc-text-left`, `akc-text-center`, `akc-text-right`, `akc-text-justify`
- **Font Size**: `akc-text-xs` to `akc-text-9xl`, `akc-ft-size-*`
- **Font Weight**: `akc-font-thin` to `akc-font-black`, `akc-fw-*`
- **Text Decoration**: `akc-underline`, `akc-overline`, `akc-line-through`, `akc-no-underline`
- **Text Transform**: `akc-uppercase`, `akc-lowercase`, `akc-capitalize`, `akc-normal-case`
- **Line Height**: `akc-leading-*`, `akc-leading-tight`, `akc-leading-normal`, `akc-leading-loose`
- **Letter Spacing**: `akc-tracking-*`

### 🎨 **Color Utilities**
- **Text Colors**: `akc-text-blue`, `akc-text-green`, `akc-text-red`, `akc-text-yellow`, `akc-text-purple`, `akc-text-pink`, `akc-text-orange`, `akc-text-gray`, `akc-text-brown`, `akc-text-teal`, `akc-text-tralim`
- **Background Colors**: `akc-bg-blue`, `akc-bg-green`, `akc-bg-red`, `akc-bg-yellow`, `akc-bg-purple`, `akc-bg-pink`, `akc-bg-orange`, `akc-bg-gray`, `akc-bg-brown`, `akc-bg-teal`, `akc-bg-tralim`
- **Opacity Variants**: `akc-bg-blue-10` to `akc-bg-blue-90` for all colors

### 🔲 **Border Utilities**
- **Border Width**: `akc-border-0`, `akc-border`, `akc-border-2`, `akc-border-4`, `akc-border-8`
- **Border Style**: `akc-border-solid`, `akc-border-dashed`, `akc-border-dotted`, `akc-border-double`
- **Border Colors**: `akc-border-blue`, `akc-border-green`, `akc-border-red`, etc.
- **Border Radius**: `akc-rounded-none` to `akc-rounded-full`, individual corner utilities

### ✨ **Visual Effects**
- **Opacity**: `akc-opacity-0` to `akc-opacity-100`
- **Transform**: `akc-scale-*`, `akc-rotate-*`, `akc-translate-*`, `akc-skew-*`
- **Transitions**: `akc-transition-*`, `akc-duration-*`, `akc-ease-*`
- **Animations**: `akc-animate-spin`, `akc-animate-ping`, `akc-animate-pulse`, `akc-animate-bounce`
- **Filters**: `akc-blur-*`, `akc-brightness-*`, `akc-contrast-*`, `akc-grayscale`, `akc-invert`, `akc-saturate-*`, `akc-sepia`
- **Backdrop Filters**: `akc-backdrop-blur-*`

### 📱 **Responsive Utilities**
- **Breakpoints**: `sm:` (576px+), `md:` (768px+), `lg:` (992px+), `xl:` (1200px+), `xxl:` (1400px+)
- **Responsive Classes**: `akc-sm-d-flex`, `akc-md-text-center`, `akc-lg-justify-between`, etc.

### 🎯 **Display & Visibility**
- **Display**: `akc-d-none`, `akc-d-block`, `akc-d-inline`, `akc-d-inline-block`, `akc-d-flex`, `akc-d-grid`
- **Overflow**: `akc-oflow-hidden`, `akc-oflow-visible`, `akc-oflow-scroll`, `akc-oflow-auto`
- **Cursor**: `akc-cur-pointer`, `akc-cur-default`, `akc-cur-wait`, `akc-cur-text`, etc.

### 🎨 **Box Shadow**
- **Shadows**: `akc-box-shadow-xxx-small` to `akc-box-shadow-x-large`

### 🎯 **Z-Index**
- **Layering**: `akc-z-0`, `akc-z-10`, `akc-z-20`, `akc-z-30`, `akc-z-40`, `akc-z-50`, `akc-z-auto`

## Usage Examples

### Basic Layout
```html
<div class="akc-d-flex akc-justify-center akc-items-center akc-p-4 akc-bg-blue akc-text-white akc-rounded-lg">
  <h1 class="akc-text-2xl akc-font-bold">Hello World!</h1>
</div>
```

### Responsive Design
```html
<div class="akc-d-flex akc-flex-col akc-md-flex-row akc-gap-4 akc-p-4">
  <div class="akc-w-full akc-md-w-1-2 akc-bg-green akc-p-4 akc-rounded">Column 1</div>
  <div class="akc-w-full akc-md-w-1-2 akc-bg-blue akc-p-4 akc-rounded">Column 2</div>
</div>
```

### Interactive Elements
```html
<button class="akc-bg-tralim akc-text-white akc-px-4 akc-py-2 akc-rounded akc-transition akc-hover-bg-tralim-80 akc-cur-pointer">
  Click Me
</button>
```

### Grid Layout
```html
<div class="akc-d-grid akc-grid-cols-1 akc-md-grid-cols-2 akc-lg-grid-cols-3 akc-gap-4">
  <div class="akc-bg-gray akc-p-4 akc-rounded">Item 1</div>
  <div class="akc-bg-gray akc-p-4 akc-rounded">Item 2</div>
  <div class="akc-bg-gray akc-p-4 akc-rounded">Item 3</div>
</div>
```

## Installation

Simply include the CSS file in your HTML:

```html
<link rel="stylesheet" href="akc-sheep.css">
```

## Customization

All classes are prefixed with `akc-` to avoid conflicts with other CSS frameworks. The framework includes:

- **Brand Colors**: Tralim orange (`#F58021`) and secondary colors
- **Comprehensive Spacing**: 0 to 64 units with auto values
- **Full Color Palette**: Blue, green, red, yellow, purple, pink, orange, gray, brown, teal
- **Responsive Design**: Mobile-first approach with 5 breakpoints
- **Modern CSS**: Flexbox, Grid, CSS Grid, Transforms, Animations, Filters

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid support required for grid utilities
- CSS Custom Properties support for advanced features

## License

This project is open source and available under the MIT License.

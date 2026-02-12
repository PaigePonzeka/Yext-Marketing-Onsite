# Brand Colors Reference

Official color palette for Marketing Web Engineering Team projects.

---

## Primary Colors

### Brand Blue
- **Hex:** `#3961E8`
- **RGB:** `rgb(57, 97, 232)`
- **Usage:** Primary brand color, CTAs, links, highlights

### Black
- **Hex:** `#000000`
- **RGB:** `rgb(0, 0, 0)`
- **Usage:** Text, headings, borders

### White
- **Hex:** `#FFFFFF`
- **RGB:** `rgb(255, 255, 255)`
- **Usage:** Backgrounds, text on dark backgrounds

---

## Color Palette Quick Reference

```css
:root {
  --brand-primary: #3961E8;
  --brand-black: #000000;
  --brand-white: #FFFFFF;
}
```

---

## Usage Examples

### CSS
```css
.button-primary {
  background-color: #3961E8;
  color: #FFFFFF;
}

.text-primary {
  color: #000000;
}
```

### Tailwind CSS
```html
<button class="bg-[#3961E8] text-white">Click Me</button>
```

### React/JSX
```jsx
const brandColors = {
  primary: '#3961E8',
  black: '#000000',
  white: '#FFFFFF'
};
```

---

## Accessibility Notes

- Brand Blue (#3961E8) on White (#FFFFFF): **WCAG AA compliant**
- White (#FFFFFF) on Brand Blue (#3961E8): **WCAG AA compliant**
- Ensure sufficient contrast ratios when using these colors for text

---

**Last Updated:** February 12, 2026

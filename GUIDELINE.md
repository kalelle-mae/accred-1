# AccrediTrack HTML Coding Guidelines

## Overview
These guidelines ensure clean, readable, and maintainable HTML code 
across the project while preserving original design and styling.

---

## Formatting Rules

### Line Length & Indentation
- **Maximum 80 characters per line**
- **2-space indentation** (no tabs)
- Break long attributes across multiple lines
- Align closing tags with their corresponding opening tags

### Example:
```html
<table border="1" bordercolor="#CD853F" 
       cellpadding="10" width="100%">
  <tr>
    <td align="center">
      <font color="#8B0000">
        Content here
      </font>
    </td>
  </tr>
</table>
```

---

## Structure Rules

### Nesting & Hierarchy
- **Maximum 3-4 nesting levels** — avoid deep nesting
- Maintain clean, readable hierarchy
- Use consistent spacing between elements
- Keep code simple and maintainable

### Best Practices
- One element per line when breaking attributes
- Group related elements together
- Add blank lines between major sections
- Preserve original design/styling intent

---

## When Reviewing Code
✅ Check line length (80 char max)  
✅ Verify 2-space indentation  
✅ Confirm proper tag alignment  
✅ Ensure nesting doesn't exceed 3-4 levels  
✅ Maintain original design integrity
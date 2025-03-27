# 2024/2025 Master Timetable

This repository contains the HTML/CSS implementation of the 2024/2025 academic year master timetable based on the provided image.

## Accessibility Features

1. **Semantic HTML Structure**:
   - Proper use of `<table>`, `<thead>`, `<tbody>`, and `<th>` elements
   - `scope` attributes for all header cells to improve screen reader compatibility

2. **Visual Design**:
   - High contrast colors for readability
   - Distinct styling for different types of periods (breaks, lunch, etc.)
   - Zebra striping for better row differentiation

3. **Responsive Considerations**:
   - Table can scroll horizontally on small screens
   - Adjusted font sizes for smaller viewports

4. **Teacher Key**:
   - Included at the bottom of the timetable for reference
   - Clearly labeled and styled for easy reference

## Preview Image

![Timetable Preview](timetable_preview.png "2024/2025 Master Timetable")

## Implementation Notes

- Used extensive `rowspan` and `colspan` to match the complex merging in the original timetable
- Vertical text for day headers to save horizontal space
- Compact styling to fit all periods while maintaining readability
- Teacher reference numbers included with subject codes

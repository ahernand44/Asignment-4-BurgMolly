Polish Audit

## Colors I'm using
- #252525 (borders on nav, header, section, footer)
- #252d20 (testimonial and footer background) ← close to #252525 but not the same
- #ecc59c (header and projects background, plus testimonial and footer text)
- #888080 (dotted border on project articles)

## Spacing values I'm using
- 3rem (body padding)
- 1rem (grid gap, section padding, article padding, nav link margin, article margin-top)
- 0.5rem (button margin-top)
- 0.5px (section borders)
- Bugs: `margin-bottom: 1 rem` (space makes it invalid) and `margin: 3` (no unit)

## Fonts I'm using
- system-ui, sans-serif for the whole body
- No separate heading font set




## What made the biggest difference
1. **Footer text color.** The footer text was black on dark green (#252d20), which is roughly a 1.5:1 contrast ratio, so it was basically unreadable. I changed it to the peach (#ecc59c), which is around 8.8:1, and now it's easy to read.
2. **Making the two columns equal.** The testimonial box started on column 2 (`2 / 7`) while the projects box started on column 7, so there was a weird empty gap on the left and the boxes were different widths. Changing it to `1 / 7` made both exactly 6 columns, and the page looks way more balanced.
3. **Custom properties.** I moved my colors, spacing, and fonts into `:root` variables and merged #252525 and #252d20 into one dark green. Now if I want to change the palette I only have to edit one line instead of hunting through the whole file.

## Midterm reflection
I think the color palette is working really well. The dark green and peach feel cozy and fit the sewing theme. Im really happy with how th efirst image is centered now and just looks way more like a real website. Also i was able to make the testimonial and project parts equal boxes side by side with the quote centered feel clean and easy to scan. Before the final I still want to fix the mobile layout and clean up my image filenames, and make the Sewing 101 section match the rest of the page.
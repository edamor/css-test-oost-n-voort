# Goal

You must able to identify the reason of why `<aside>` tag is being pushed on next line.

And must also fix it.

### Note

`<section>` tag must have a width of 75%

`<aside>` tag must have a width of 25%

You must not edit `index.html`

# Expected Output

<img src="https://cdn.glitch.com/7373e19d-cfff-4c35-8ae0-a64502512e61%2Fa33902fd-7b6d-44eb-86ed-9a4505811745.image.png?v=1610011580923">

# Your Answer Here

_type here what is the issue and how you solve it_

The issue was caused by the padding property of the elements.

The size of the padding was being added on top of the defined widths of both the
section and aside tags.

The defined widths of these elements can be styled in such a way
that the width will take into account the padding that was being applied.

The widths of these elements are still 75% and 25% respectively. However, I will
use the calc function to handle the miniscule adjustments necessary to make
these elements take up the 100% width of the screen.

To solve the issue, I did the following:
  1. I used the calc function to deduct the 1rem padding size from the given width measurements.
  2. Refreshed the page to make sure it works.
  3. Done.

Responsive validation completed for the bilingual menu patch.

At 390 x 844 mobile width, the hero stacks vertically, the logo remains contained, the action row and EN language toggle fit without horizontal overflow, category pills remain horizontally scrollable, and the featured dish card fits the viewport. The item grid changes to one column under 520px for readable cards and touch targets.

At 768 x 1024 tablet width, the two-column hero remains balanced, category pills stay on one horizontal scroll row, the featured dish card uses the wider layout, and there is no visible clipping or overflow. The mobile-specific rules preserve comfortable padding, larger touch targets, and a one-column menu grid on narrow phones.

The English toggle was tested in the browser: it changes document direction to LTR, updates the page title, navigation labels, feature dish, descriptions, category names, tags, prices to IQD, add-to-order buttons, search placeholder, cart labels, and footer copy. The toggle label changes from EN to عربي for returning to Arabic.

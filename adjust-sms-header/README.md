# Prevent text overlap in SMS page header

This patch modifies the SMS conversation page so that the recipient name and the "sticky date box" don't overlap. This is visible mosty on Sony Xperia XA2 Ultra with very large font size, but the patch should calculate the position fine on all devices.

- Recalculate top margin for the sticky date box in portrait view
- Remove padding from the sticky date box in landscape view

## Changelog

---

1.0.0

- Initial release for 4.0+


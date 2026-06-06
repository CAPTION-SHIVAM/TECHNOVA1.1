Store student certificate files in this folder using the SRNO-style reference as the file name.

Examples:
- 01technova2026.pdf
- 02technova2026.png
- 03technova2026.jpg

In certificate.html, each registry entry can point to one of these files via the `file` property.
QR codes on certificates should open certificate.html with `?ref=REFERENCE` so the page verifies the same certificate automatically.

GST SPLIT — INSTALLABLE IPHONE CALCULATOR
========================================

FILES:
- index.html: complete calculator, also works on a Mac when opened directly.
- manifest.webmanifest, sw.js and icons/: needed to install and run offline.

INSTALL ON AN IPHONE USING GITHUB PAGES
1. Create a new PUBLIC repository in GitHub, for example gst-split.
2. Upload the contents of this folder to the repository root (index.html,
   manifest.webmanifest, sw.js, and the icons folder). Do not upload just
   the ZIP: GitHub Pages needs the extracted files.
3. Open the repository's Settings -> Pages. Select "Deploy from a branch",
   Branch "main", folder "/ (root)". Save.
4. When GitHub Pages publishes your site, open its HTTPS URL in Safari on
   the iPhone. (Typically https://YOUR-USERNAME.github.io/gst-split/.)
5. In Safari, tap Share -> Add to Home Screen -> Add.
6. Tap the new GST Split icon to use the calculator as a standalone app.
   Once loaded, it will also work without an internet connection.

USAGE
- Use "Before GST" when entering a pretax amount.
- Use "Total paid" when entering a GST-inclusive amount, including tips.
- Tap "Tip" to enter a tax-free tip separately.
- Use "Match QBO" to match QuickBooks NPR 2.5% auto-calculated tax, or
  choose "First up / First down" to manually allocate an extra GST cent.
- Tap "QuickBooks lines" or "Copy entry" for expense line instructions.
- Tap the on-screen keypad. On a Mac, you can also use your keyboard.

EXAMPLE: TOTAL PAID $150.91, TIP $0.00
Pretax $143.72; GST $7.19; NPR 2.5% $3.59; Exempt expense $3.60.
The two lines plus the NPR auto-tax total $150.91.

NOTES
- This is a GST bookkeeping calculator, not a replacement for reviewing
  invoices or the tax status of an expense.
- The app assumes the 5% GST applies to the pretax amount, and that tips
  are not taxable. When in doubt, verify the original invoice.
- Some vendor tax rounding methods differ by one cent; the app prioritizes
  exact reconciliation to the amount charged.
- Hosting on HTTPS is needed for reliable Home Screen installation/offline
  support. Opening index.html directly on the phone is not the same.

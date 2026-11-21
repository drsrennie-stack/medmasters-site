# medmasters-site

The MedMasters Collaborative website. Plain HTML files, no build step.

## Files

| File | What it is |
|------|------------|
| `index.html` | Home page: coaching and tools |
| `chalkcast.html` | chalkcast product page |
| `legal-policies.html` | Legal and policies |
| `site.css` | Colors, fonts, and layout shared by the home page and chalkcast page |
| `images/` | Pictures used on the pages |

## How to change something

1. Open the file on github.com and press the pencil icon.
2. Press Ctrl+F (Cmd+F on a Mac) and search for the words you want to change.
3. Type the new words between the tags. Leave the `<` and `>` parts alone.
4. Press "Commit changes". The live site updates in a minute or two.

To replace a picture, upload a new file to `images/` with the same name.

## Things to fill in before launch

- `chalkcast.html`: replace `KAJABI-CHECKOUT-LINK` (it appears twice) with the checkout link for the chalkcast offer.
- `legal-policies.html`: fill in `[14]` (refund window) and `[mailing address]`.

## Adding a new tool to the home page

In `index.html`, find `<!-- === TOOLS === -->`. Copy the whole first `<div class="tool-card">` block, paste it under itself, and change the number, name, price, text, picture, and links.

## The header and footer

The menu at the top and the footer are repeated in `index.html` and `chalkcast.html`. If you change a menu link, change it in both files.

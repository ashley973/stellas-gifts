# Stella's Christmas gift boxes website

A one-page website. Everything is in `index.html`; there is nothing to install or build.

## Change the business name
Open `index.html`. Near the very top is this line:

```html
<script>window.BUSINESS_NAME = "[BUSINESS NAME]";</script>
```

Replace `[BUSINESS NAME]` with the real name (keep the quote marks). It updates the header, footer and browser tab.
Also replace the two `[BUSINESS NAME]` placeholders in the header and footer, which show if JavaScript is off.

## Change any other text
Open `index.html` and find the words you want to change (Ctrl+F / Cmd+F). Edit only the words between the tags,
for example `<h3>The Thank You</h3>`. Each section is labelled with a comment like `<!-- 2. THE BOXES -->`.

Prices are in lines like `<span class="price">$55</span>`.
The order dates appear twice: in the strip under the top section and in the final section near the bottom.

## Add the box photos
Put photos in the `images` folder with exactly these names:

| Box            | File name               |
|----------------|-------------------------|
| The Thank You  | `images/thank-you.jpg`  |
| The Good Year  | `images/good-year.jpg`  |
| The Big Cheers | `images/big-cheers.jpg` |

Photos show up automatically, replacing the "Photo coming soon" placeholder. Landscape photos work best (4:3 shape,
about 1200 × 900 pixels). Keep each file under about 300 KB so the page loads fast.
File names must be lowercase and end in `.jpg`.

## Publish changes
The site is hosted on GitHub Pages. Any change saved to the `main` branch goes live within a minute or two.

The easiest way, in the browser:
1. Open the repository on github.com.
2. To edit text: click `index.html`, click the pencil icon, make the change, then click **Commit changes**.
3. To add photos: open the `images` folder, click **Add file > Upload files**, drag the photos in, then click **Commit changes**.

## Ideas preview (`inspiration.html`)
A second version of the page showing upgrade ideas: a quote form, FAQ, customer quotes, a sharing preview
picture (`images/share.png`), better Google details and a booked-out switch. The customer quotes and FAQ answers
are examples only. All its settings (business name, form address, booked-out switch) are in one block at the top.

To make it the real homepage: replace the example quotes and FAQ answers with real ones, delete the preview
banner block and the `noindex` line, then rename it to `index.html` (replacing the old one).

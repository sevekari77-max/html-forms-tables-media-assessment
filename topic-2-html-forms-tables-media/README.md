# Topic 2 Assessment — HTML Forms, Tables and Media

This project implements the Lesson 2 assessment requirements.

## Pages

- `index.html` — accessible Contact Form with native HTML5 validation
- `table.html` — semantic Product Comparison Table
- `media.html` — HTML5 video/audio, YouTube iframe and optional Google Map iframe
- `styles.css` — shared responsive styling

## Requirements covered

### Contact Form
- Form with POST method
- Text, email, phone and URL inputs
- Date and number inputs
- Textarea
- Select dropdown
- Radio buttons
- Checkbox
- File upload
- Submit and reset buttons
- `required`, `minlength`, `maxlength`, `pattern`, `min` and `max`
- Labels linked to controls
- Fieldsets and legends

### Product Comparison Table
- Caption
- `thead`, `tbody`, `tfoot`
- `th` and `td`
- `scope="col"` and `scope="row"`
- `colspan`
- Multiple products

### Media
- Native HTML5 video
- Native HTML5 audio
- Figure and figcaption
- YouTube iframe
- Optional Google Map iframe
- iframe `title`
- iframe `sandbox`
- Referrer policy and lazy loading where appropriate

## Run

Open the folder in VS Code and use **Live Server** on `index.html`.

## Validation

Test every page with the HTML validator and manually test:
1. Required form fields.
2. Invalid email/URL/phone values.
3. Number min/max validation.
4. Textarea length validation.
5. Submit/reset controls.
6. Table structure.
7. Video/audio controls.
8. Iframe rendering and sandbox attributes.

## GitHub submission

Push the complete folder to a **public GitHub repository**. The LMS should receive the public repository URL and the Loom/YouTube demonstration URL.

## Important

The video/audio examples use publicly hosted demonstration media so the project remains small. If your LMS specifically requires media files to be stored inside the repository, download legally permitted media and place them in a `media` folder, then change the `<source>` URLs to local paths.

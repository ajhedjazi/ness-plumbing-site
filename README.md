# Hull Drain Response Landing Page

Static local lead-generation landing page for urgent blocked drain enquiries across Hull and nearby East Yorkshire areas.

## Project Structure

- `index.html` - page content, Netlify form, phone configuration, and interaction script
- `styles.css` - site styling and responsive rules
- `assets/` - reference assets

## Phone Setup

The business phone number is configured near the end of `index.html`:

```js
const PHONE_DISPLAY = "+44 7549 731381";
const PHONE_TEL = "+447549731381";
```

Use a readable number for `PHONE_DISPLAY` and the dialable international format for `PHONE_TEL`.

## Form Setup

The contact form uses Netlify Forms with the form name `drain-enquiry`. Form submissions can be viewed and routed from the Netlify site dashboard after deployment.

## Local Preview

Open `index.html` directly in a browser or serve the project folder with a static local server.

## Deployment

The site has no build step or package dependencies. Deploy the repository root as a static site.

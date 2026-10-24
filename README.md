# SAMNEX Technologies Portfolio

A responsive portfolio website for Samuel Chiemerie, built with semantic HTML5 and CSS3. It has no JavaScript, frameworks, build tools, or package-manager dependencies.

## Files

- `index.html` — page content, SEO metadata, navigation, and contact links.
- `css/style.css` — design system, responsive layout, CSS-only mobile navigation, and motion preferences.
- `assets/images/samuel-chiemerie.jpg` — portrait supplied for this portfolio.
- `assets/images/samnex-logo.png` — SAMNEX logo supplied for this portfolio.
- `assets/icons/` — reserved for any additional static icon assets.

## Open locally

1. Extract the `samnex-portfolio.zip` file.
2. Open the `portfolio` folder.
3. Open `index.html` in a modern browser.

No installation or build step is required. The Google Fonts import is optional; if you want the page to use only local assets and work without a network connection, remove the `@import` line at the top of `css/style.css`. The fallback fonts will still work.

## Personalise before publishing

1. Review the professional summary and service descriptions in `index.html`.
2. Replace the experience and education placeholders with accurate details.
3. Add real project screenshots and case studies when available.
4. Add only genuine testimonials.
5. Verify the GitHub profile URL and all contact details.
6. If you use a custom domain, update the canonical/social metadata as needed and add a canonical URL once the site is deployed.
7. Optimise the portrait/logo image files if you need smaller downloads. Keep the alt text accurate if you replace the portrait.

## Contact behaviour

- Email opens the visitor's email application using `mailto:`.
- WhatsApp opens a chat link using the supplied number.
- The project button opens the current SAMNEX Voice Lab address in a new tab.
- This static site has no contact form because sending form submissions requires a backend or a form-processing service.

## Deployment

Upload the contents of this folder to a static hosting provider that supports HTML/CSS files. Upload `index.html`, the `css` folder, and the `assets` folder together so the relative paths continue to work. A custom domain such as `www.samnex.com` must be registered and connected separately; domain registration is not guaranteed to be free.

## Accessibility and quality notes

- Uses semantic landmarks, heading hierarchy, skip link, descriptive portrait alt text, visible keyboard focus, and reduced-motion preferences.
- Navigation uses a CSS checkbox/label toggle on small screens and works without JavaScript.
- External links that open a new tab include `rel="noopener noreferrer"`.
- No Lighthouse, accessibility audit, or Core Web Vitals score is claimed. Test the deployed site in current browsers and with keyboard navigation before public launch.

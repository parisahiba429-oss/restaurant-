# Beauty & Joy website

Open `index.html` in a browser. No build step. Upload the whole folder to any web host.

## Structure
- `index.html` page content (About, Academy, address, policies text)
- `css/styles.css` colours (top of file) and layout
- `js/site.js` EDITABLE CONTENT at the top: phone, WhatsApp, social links, services, prices, packages, courses, gallery, FAQ, hours
- `images/` all photos (WebP)

## Common edits
- Prices: change `PRICE` or the third value in `S("Name","Description","From ₹500")`
- Opening hours: edit `HOURS`
- WhatsApp: set `CONFIG.whatsapp` (country code + number, e.g. 916393598841). It currently reuses the phone number, so verify it
- Photos: replace a file in `images/` keeping the same name, or add one and list it in `GALLERY`
- Instagram/Facebook: fill `CONFIG.instagram` / `CONFIG.facebook`; they stay hidden until set

## Still needs setup
- Verify the Google rating (4.7 / 1,829) and the Google reviews and directions links
- Confirm the WhatsApp number, hours, prices, package details, course fees/duration
- Forms have no backend: they validate, then open a prefilled WhatsApp message. For email/CRM, connect Formspree, Google Forms or a booking tool
- Add a nail-treatment photo for the gallery, and the owner's own About text
- Add a full privacy policy; domain, hosting and analytics

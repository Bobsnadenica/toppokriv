# toppokriv.com

Static Bulgarian roofing website published from the root of this repository with GitHub Pages. The source was moved from `theprivilegedcompany.com/dev/MaistorPlus`.

## Pages

- `/` — home and enquiry form
- `/uslugi/remont-na-pokrivi/` — roof repair service page for Bulgaria
- `/blog/` — article index
- `/blog/remont-na-pokrivi-ceni-i-faktori/`
- `/blog/kak-da-razpoznaete-priznatsi-na-povreden-pokriv/`

The site uses “Топ Покрив” branding and phone `0893 871 252`. Current service area is all of Bulgaria, with a base in Sofia. Contact links and the enquiry form use `info@toppokriv.com`; Cloudflare Email Routing forwards that address to the owner’s verified destination inbox. The form posts through FormSubmit, which requires separate activation whenever its recipient address changes. Confirm both the Cloudflare route and FormSubmit delivery before relying on the form for customers. GitHub Pages does not run PHP.

The canonical URLs and structured data use `https://toppokriv.com`. The `www` hostname redirects to the apex through GitHub Pages when both DNS records are present.

## Search

`robots.txt` points crawlers to `sitemap.xml`. The sitemap lists the homepage, roof-repair service page, blog, and both articles. Keep the Google Search Console verification TXT record in Cloudflare DNS so the domain property remains verified. Update the sitemap when public pages are added or removed.

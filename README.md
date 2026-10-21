# Aditya Adinata — Personal Portfolio

A single-page personal developer portfolio with an editorial private-capital visual direction. It is built with native PHP, semantic HTML, and vanilla CSS. The site has no database, JavaScript, Composer, npm, or production build step.

## Owner and school details

- Full name: **Aditya Adinata** (confirmed by the owner)
- Education: Grade XII vocational student in software development (RPL/PPLG), per the brief
- Exact class: **[add exact class before school submission]**
- GitHub repository for this new portfolio: **[add repository URL if published]**
- Live portfolio domain: **[add domain URL after deployment]**

## Project status and accuracy

All seven entries use screenshots supplied by the owner. The text only describes features visible in those screenshots. `includes/data.php` deliberately leaves most project technology stacks and contribution fields empty until verified. The library screenshot shows a Laravel browser tab and the project is labeled Laravel/PHP. DitiketinAja and RD Softworks have live URLs that returned HTTP 200 during local verification on 21 October 2026. Other screenshots show local or demo views, so no public link is displayed for them.

Before publishing as a finished portfolio, review the descriptions, confirm your specific contribution and technology stack for each project, and replace any screenshot that contains browser chrome with a clean capture if desired. Check whether the public GitHub profile is still the one you want to display.

## Structure

```text
index.php                    Main page and semantic sections
includes/data.php            Profile, expertise, and project arrays
includes/helpers.php         Output escaping and URL validation helpers
includes/header.php          Document head and navigation
includes/footer.php          Footer and closing markup
includes/components/         Reusable project card
assets/css/style.css         Design system and responsive rules
assets/images/               Portrait, favicon, and seven screenshots
.htaccess                    Disable directory listing
AI_USAGE.md                  AI assistance and student-change record
MASTER_PROMPT.md             Original supplied project brief
```

## Run locally

1. Place this directory in the XAMPP `htdocs` folder.
2. Start Apache in XAMPP.
3. Open `http://localhost/Porto-project/`.
4. If Apache is unavailable, run `php -S localhost:8000` from this directory for local testing only, then open `http://localhost:8000/`.

PHP 8.2 or a compatible PHP 8 version is recommended. No database setup is required.

## Deploy to cPanel

1. Verify the content in `includes/data.php`, images, links, and exact class details.
2. Make a ZIP containing **the contents of this folder**, so `index.php` is at the ZIP root.
3. In cPanel File Manager, open the **actual document root for your domain**. This can differ from the account's main `public_html` folder.
4. Upload and extract the ZIP there. Confirm `index.php`, `includes/`, and `assets/` sit directly in that document root.
5. Confirm the domain is using a compatible PHP version.
6. Test the site over HTTPS after the domain's SSL certificate is active. Check images, anchor navigation, mobile menu, and external links.

Do not enable an HTTPS redirect until SSL works on the domain. There is no rewrite rule or deployment secret.

## Screenshot and final review checklist

- [x] Library Management System screenshot received
- [x] KLOKIN screenshot received
- [x] RD Softworks screenshot received
- [x] Verion EDU screenshot received
- [x] Nalara screenshot received
- [x] Arunika screenshot received
- [x] DitiketinAja screenshot received
- [ ] Confirm project role, exact stack, and final descriptions
- [ ] Confirm exact class and desired professional contact address
- [ ] Check the deployed domain and mobile layout after upload

The hero portrait was supplied by the owner and stored locally as an optimized WebP image. Replace `assets/images/profile.webp` if a different portrait is preferred.
"# Porto-Adit" 

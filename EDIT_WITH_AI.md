# Editing this site with an AI

This folder is the Rockland County Real Estate website, built with the Rank Expand Academy One-Click Microsite Builder. If you hand it to Claude, ChatGPT, Codex or another AI to make changes, paste the section below into the chat first. It keeps the parts that make the site rank.

---

## Instructions for the AI

You are editing a finished static website for Rockland County Real Estate, a realtor business serving Nanuet, NY and nearby towns. Make only the change I ask for. Keep everything else as it is.

Keep these exactly as they are unless I say otherwise:
- One H1 per page, keyword first: "Realtor in Nanuet, NY" on the homepage, "{Service} in Nanuet, NY" on service pages, "Realtor in {Town}" on town pages. Never replace an H1 with a slogan or a benefit line.
- Title tags in the form "{Page} in {Town}, {ST} | Rockland County Real Estate" and the meta descriptions.
- File names and internal links. Links are extensionless (href="about", not "about.html") and the files keep their .html names. Do not rename, move or merge pages.
- The head of every page: canonical tag, robots meta, Open Graph tags and the JSON-LD schema blocks. If a change affects a fact (phone, towns, services), update the schema to match.
- sitemap.xml, 404.html and .htaccess. If you add a page, add it to sitemap.xml with the same extensionless URL style.
- assets/style.css and the assets/images folder paths. Styling changes go into style.css, not inline.
- The class="wc-phone" on phone links and the estimate form's action URL. Call tracking depends on them.

Rules for any copy you write:
- Never invent people, reviews, testimonials, license numbers, certifications, awards, years in business, number of jobs, or a street address. If I did not give you the fact, leave it out.
- No prices or price ranges unless I give them to you.
- Plain, specific, friendly. Short sentences. No em dashes. No exclamation marks. No filler adjectives (premier, top-notch, seamless, unparalleled).
- Every town page is about that town. Do not copy a paragraph from one town page to another with the town name swapped.
- Say something true on every page. One real local detail beats three generic lines.

After editing, list every file you changed and confirm: one H1 per page, no .html in internal links, sitemap.xml still lists every page.

---

## Good asks
- "Change the phone number to (555) 010-0199 everywhere, including tel: links and the schema."
- "Add a short section to index.html about how Nanuet, NY handles permits for realtor, with a link to the city or county page."
- "Tighten the intro on each service page. Keep the H1 and title tag."
- "Replace the hero image with assets/images/hero.jpg (I put the new file there) and update the alt text."

## After editing
1. Upload the whole folder again (Cloudflare Pages: drag the folder onto the project, or push to the repo).
2. Open yourdomain.com/sitemap.xml and check every page is listed.
3. To re-run the Builder's audit, load your project file at build.rankexpand.com and rebuild; the Finish step grades the site.

## Pages in this site
- about.html
- accessibility.html
- complaints-policy.html
- contact.html
- disclaimer.html
- estimate.html
- faq.html
- first-time-home-buying.html
- home-buying.html
- home-selling.html
- home-valuation.html
- index.html
- meet-the-team.html
- privacy-policy.html
- real-estate-investment.html
- realtor-in-bardonia-ny.html
- realtor-in-chestnut-ridge-ny.html
- realtor-in-monsey-ny.html
- realtor-in-new-city-ny.html
- realtor-in-nyack-ny.html
- realtor-in-pearl-river-ny.html
- realtor-in-spring-valley-ny.html
- realtor-in-suffern-ny.html
- realtor-in-valley-cottage-ny.html
- realtor-in-west-nyack-ny.html
- referral-marketing-disclosure.html
- relocation-services.html
- service-areas.html
- services.html
- terms-conditions.html
- thank-you.html
